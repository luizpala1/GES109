### [Códigos](#)
Nessa seção estão disponíveis alguns códigos que iremos trabalhar durante a disciplina GES-109. 


document.addEventListener('DOMContentLoaded', function() {
    // Função para gerar dados de uma distribuição normal
    function generateNormalDistributionData(mean, stdDev, size) {
        const data = [];
        for (let i = 0; i < size; i++) {
            data.push((Math.random() * stdDev) + mean);
        }
        return data;
    }

    // Parâmetros da distribuição normal
    const mean = 0;
    const stdDev = 1;
    const dataSize = 100;

    // Gerar dados
    const data = generateNormalDistributionData(mean, stdDev, dataSize);

    // Criar gráfico
    const ctx = document.getElementById('normalDistributionChart').getContext('2d');
    new Chart(ctx, {
        type: 'line',
        data: {
            labels: Array.from({ length: dataSize }, (_, i) => i + 1),
            datasets: [{
                label: 'Distribuição Normal',
                data: data,
                borderColor: 'rgba(75, 192, 192, 1)',
                borderWidth: 1,
                fill: false
            }]
        },
        options: {
            scales: {
                x: {
                    type: 'linear',
                    position: 'bottom'
                },
                y: {
                    min: -3,
                    max: 3
                }
            }
        }
    });
});
