<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Interactive Skill Icons</title>
    <style>
        .skill-icons {
            display: flex;
            gap: 20px;
        }
        .skill-icon {
            width: 50px;
            height: 50px;
            transition: transform 0.3s ease;
        }
        .skill-icon:hover {
            transform: scale(1.2); /* Enlarges the icon */
        }
    </style>
</head>
<body>
    <div class="skill-icons">
        <img class="skill-icon" src="https://skillicons.dev/icons?i=ts" alt="TypeScript">
        <img class="skill-icon" src="https://skillicons.dev/icons?i=js" alt="JavaScript">
        <img class="skill-icon" src="https://skillicons.dev/icons?i=react" alt="React">
        <img class="skill-icon" src="https://skillicons.dev/icons?i=nodejs" alt="Node.js">
        <img class="skill-icon" src="https://skillicons.dev/icons?i=mongodb" alt="MongoDB">
    </div>
</body>
</html>
