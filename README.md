<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <style>
        /* CSS styles for the infographic */
        .infographic {
            width: 100%;
            max-width: 800px;
            margin: 0 auto;
        }

        .activity {
            fill: #3498db;
            transition: fill 0.3s;
        }

        .activity:hover {
            fill: #e74c3c;
        }
    </style>
    <title>Daily Routine Infographic</title>
</head>
<body>
    <div class="infographic">
        <!-- SVG elements for the daily routine -->
        <svg xmlns="http://www.w3.org/2000/svg" width="800" height="400">
            <rect class="activity" x="50" y="50" width="100" height="100" />
            <rect class="activity" x="200" y="50" width="100" height="100" />
            <rect class="activity" x="350" y="50" width="100" height="100" />
            <!-- Add more SVG elements for your routine activities -->
        </svg>
    </div>
    <script>
        // JavaScript for interactivity
        const activities = document.querySelectorAll('.activity');
        
        activities.forEach(activity => {
            activity.addEventListener('click', () => {
                alert('You clicked an activity!');
            });
        });
    </script>
</body>
</html>
