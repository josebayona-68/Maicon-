<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>MAICON 2025 | Personalized Agenda</title>
    <script src="https://cdn.tailwindcss.com"></script>
    <script src="https://cdn.jsdelivr.net/npm/chart.js"></script>
    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
    <link href="https://fonts.googleapis.com/css2?family=Inter:wght@400;500;600;700;900&display=swap" rel="stylesheet">
    <style>
        body {
            font-family: 'Inter', sans-serif;
        }
        .chart-container {
            position: relative;
            width: 100%;
            max-width: 400px;
            margin-left: auto;
            margin-right: auto;
            height: 300px;
            max-height: 400px;
        }
        @media (min-width: 768px) {
            .chart-container {
                height: 350px;
            }
        }
        .timeline-item::before {
            content: '';
            position: absolute;
            top: 1.25rem;
            left: -0.5rem;
            transform: translateX(-50%);
            width: 1.25rem;
            height: 1.25rem;
            border-radius: 50%;
            background-color: #3357FF;
            border: 4px solid #F0F4F8;
        }
    </style>
</head>
<body class="bg-gray-100" style="background-color: #F0F4F8;">

    <header class="bg-white shadow-md sticky top-0 z-10">
        <div class="max-w-7xl mx-auto py-6 px-4 sm:px-6 lg:px-8 text-center">
            <h1 class="text-4xl font-extrabold tracking-tight text-gray-900" style="color: #0B1C48;">Your Personalized MAICON 2025 Agenda</h1>
            <p class="mt-2 text-lg text-gray-600">A Strategic & Tactical Plan for Grassroots Strategies & Grassroots Media</p>
        </div>
    </header>

    <main class="max-w-7xl mx-auto py-12 px-4 sm:px-6 lg:px-8">
        <div class="space-y-16">
            
            <div>
                <h2 class="text-3xl font-bold text-center mb-10" style="color: #0B1C48;">Day 1: Tuesday, Oct 14 - Arrival & Immersion</h2>
                <div class="relative pl-8 border-l-4 border-gray-300">
                    
                    <div class="mb-12 relative timeline-item">
                        <div class="bg-white rounded-lg shadow-xl p-6 border-l-4" style="border-color: #FF5733;">
                            <span class="text-sm font-semibold uppercase tracking-wider text-gray-500">1:00 PM - 4:00 PM</span>
                            <h3 class="mt-2 text-2xl font-bold" style="color: #0B1C48;">Workshop: AI for B2B Content and Lead Generation</h3>
                            <p class="mt-3 text-base text-gray-600">This workshop is the perfect starting point, providing immediate, actionable insights for both Grassroots Media's content creation and Grassroots Strategies' lead generation efforts. It's a hands-on session to kickstart your conference with practical AI applications.</p>
                            <p class="mt-2 text-sm font-medium text-gray-500">Speaker: Andy Crestodina</p>
                        </div>
                    </div>

                    <div class="relative timeline-item">
                        <div class="bg-white rounded-lg shadow-xl p-6 border-l-4" style="border-color: #FF33A1;">
                            <span class="text-sm font-semibold uppercase tracking-wider text-gray-500">6:30 PM - 8:30 PM</span>
                            <h3 class="mt-2 text-2xl font-bold" style="color: #0B1C48;">Networking: Opening Night Meetup 🤝</h3>
                            <p class="mt-3 text-base text-gray-600">An essential event to build connections from the very beginning. Use this opportunity to meet speakers, fellow agency owners, and potential partners in a relaxed setting. Your goal is to establish a foundation for deeper conversations over the next two days.</p>
                            <p class="mt-2 text-sm font-medium text-gray-500">Location: Hofbräuhaus Cleveland</p>
                        </div>
                    </div>

                </div>
            </div>

            <div>
                <h2 class="text-3xl font-bold text-center mb-10" style="color: #0B1C48;">Day 2: Wednesday, Oct 15 - Strategic Deep Dive</h2>
                <div class="grid grid-cols-1 md:grid-cols-2 gap-8 items-center mb-12">
                     <div class="bg-white rounded-lg shadow-xl p-6">
                        <h3 class="text-2xl font-bold text-center" style="color: #0B1C48;">Balancing Strategy & Application</h3>
                        <p class="mt-3 text-base text-gray-600 text-center">Wednesday's plan is designed to provide high-level insights for Grassroots Strategies while gathering tactical tools for Grassroots Media. The day is split between understanding leadership perspectives and discovering practical AI applications you can implement immediately.</p>
                        <div class="chart-container">
                            <canvas id="day2FocusChart"></canvas>
                        </div>
                    </div>
                    <div class="relative pl-8 border-l-4 border-gray-300">
                        <div class="mb-8 relative timeline-item">
                            <div class="bg-white rounded-lg shadow-md p-4">
                                <span class="text-xs font-semibold text-gray-500">9:15 AM</span>
                                <p class="font-bold">Keynote: The Move 37 Moment for Knowledge Workers</p>
                            </div>
                        </div>
                         <div class="mb-8 relative timeline-item">
                            <div class="bg-white rounded-lg shadow-md p-4">
                                <span class="text-xs font-semibold text-gray-500">10:30 AM</span>
                                <p class="font-bold">Breakout: 30 AI Tools in 30 Minutes</p>
                            </div>
                        </div>
                        <div class="mb-8 relative timeline-item">
                            <div class="bg-white rounded-lg shadow-md p-4">
                                <span class="text-xs font-semibold text-gray-500">1:00 PM</span>
                                <p class="font-bold">Breakout: Lessons from the C-Suite</p>
                            </div>
                        </div>
                        <div class="relative timeline-item">
                            <div class="bg-white rounded-lg shadow-md p-4">
                                <span class="text-xs font-semibold text-gray-500">5:00 PM</span>
                                <p class="font-bold">Networking: Happy Hour 🍻</p>
                            </div>
                        </div>
                    </div>
                </div>
            </div>
            
            <div>
                <h2 class="text-3xl font-bold text-center mb-10" style="color: #0B1C48;">Day 3: Thursday, Oct 16 - Advanced Applications & Departure</h2>
                <div class="relative pl-8 border-l-4 border-gray-300">
                    
                    <div class="mb-12 relative timeline-item">
                        <div class="bg-white rounded-lg shadow-xl p-6 border-l-4" style="border-color: #33FF57;">
                            <span class="text-sm font-semibold uppercase tracking-wider text-gray-500">9:00 AM - 9:45 AM</span>
                            <h3 class="mt-2 text-2xl font-bold" style="color: #0B1C48;">Breakout: Beyond Automation: How AI Became My Ultimate Thought Partner</h3>
                            <p class="mt-3 text-base text-gray-600">This session is tailor-made for Grassroots Strategies. It elevates the conversation from simple automation to using AI for core business strategy, a high-value service to offer clients. Learn how to position AI as a strategic partner.</p>
                            <p class="mt-2 text-sm font-medium text-gray-500">Speaker: Jen Taylor</p>
                        </div>
                    </div>

                    <div class="mb-12 relative timeline-item">
                        <div class="bg-white rounded-lg shadow-xl p-6 border-l-4" style="border-color: #F1C40F;">
                            <span class="text-sm font-semibold uppercase tracking-wider text-gray-500">10:00 AM - 10:45 AM</span>
                            <h3 class="mt-2 text-2xl font-bold" style="color: #0B1C48;">Breakout: How AI Can Elevate Human Marketing Creativity</h3>
                             <p class="mt-3 text-base text-gray-600">A crucial session for Grassroots Media. This directly addresses how to blend AI tools with human creativity to produce superior marketing content, ensuring your media services remain innovative and valuable. It's about augmentation, not replacement.</p>
                            <p class="mt-2 text-sm font-medium text-gray-500">Speaker: Dale Bertrand</p>
                        </div>
                    </div>
                    
                    <div class="relative timeline-item">
                        <div class="bg-white rounded-lg shadow-xl p-6 border-l-4" style="border-color: #3357FF;">
                            <span class="text-sm font-semibold uppercase tracking-wider text-gray-500">11:00 AM Onwards</span>
                            <h3 class="mt-2 text-2xl font-bold" style="color: #0B1C48;">Final Connections & Departure ✈️</h3>
                            <p class="mt-3 text-base text-gray-600">Use the final morning networking breaks and lunch to solidify connections made. Exchange contact information and schedule follow-ups. Depending on your flight, aim to catch the closing remarks to wrap up the key themes of the conference before heading out.</p>
                        </div>
                    </div>

                </div>
            </div>

        </div>
    </main>

    <footer class="bg-white mt-16">
        <div class="max-w-7xl mx-auto py-6 px-4 sm:px-6 lg:px-8 text-center text-gray-500">
            <p>&copy; 2025 Personalized Agenda Generator. Have a great conference!</p>
        </div>
    </footer>

    <script>
        function wrapLabel(str, maxWidth) {
            if (str.length <= maxWidth) {
                return str;
            }
            const words = str.split(' ');
            const lines = [];
            let currentLine = '';
            for (const word of words) {
                if ((currentLine + ' ' + word).trim().length > maxWidth) {
                    lines.push(currentLine.trim());
                    currentLine = word;
                } else {
                    currentLine = (currentLine + ' ' + word).trim();
                }
            }
            if (currentLine) {
                lines.push(currentLine.trim());
            }
            return lines;
        }

        const ctx = document.getElementById('day2FocusChart').getContext('2d');
        new Chart(ctx, {
            type: 'doughnut',
            data: {
                labels: ['Strategic Focus', 'Applied AI Tools'],
                datasets: [{
                    label: 'Session Focus',
                    data: [50, 50],
                    backgroundColor: [
                        '#3357FF',
                        '#FF5733',
                    ],
                    borderColor: [
                        '#FFFFFF',
                        '#FFFFFF',
                    ],
                    borderWidth: 4
                }]
            },
            options: {
                responsive: true,
                maintainAspectRatio: false,
                cutout: '70%',
                plugins: {
                    legend: {
                        position: 'bottom',
                        labels: {
                            padding: 20,
                            font: {
                                size: 14,
                                weight: '500'
                            }
                        }
                    },
                    tooltip: {
                        callbacks: {
                            title: function(tooltipItems) {
                                const item = tooltipItems[0];
                                let label = item.chart.data.labels[item.dataIndex];
                                if (Array.isArray(label)) {
                                  return label.join(' ');
                                } else {
                                  return label;
                                }
                            }
                        }
                    }
                }
            }
        });
    </script>
</body>
</html>


https://gemini.google.com/u/1/app/9cf2e98ae5a58e86?utm_source=gws&utm_medium=web&utm_campaign=gemrise_wfac_message_variant_1&pli=1 
<img width="468" height="658" alt="image" src="https://github.com/user-attachments/assets/174593ea-5ed8-4921-a8af-5a2e22c27ac1" />
