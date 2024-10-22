<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Interactive 3D Starry Space</title>
    <style>
        body, html {
            margin: 0;
            padding: 0;
            overflow: hidden;
            background: black;
        }
        .highlighted-star {
            position: absolute;
            top: 20px;
            left: 20px;
            color: #00aaff;
            font-size: 24px;
            font-weight: bold;
        }
        #inputForm {
            position: absolute;
            top: 20px;
            right: 20px;
            z-index: 1;
            color: white;
        }
    </style>
</head>
<body>
    <div class="highlighted-star">Mohamed</div>
    <div id="inputForm">
        <label for="name">Enter your name or message:</label>
        <input type="text" id="name" placeholder="Your Name/Message">
        <button onclick="claimStar()">Claim Star</button>
    </div>
    <script src="https://cdnjs.cloudflare.com/ajax/libs/three.js/r128/three.min.js"></script>
    <script>
        let userMessage = '';

        function claimStar() {
            const input = document.getElementById('name').value;
            userMessage = input ? input : 'Anonymous';
            alert(`You've claimed a star with the message: "${userMessage}"`);
        }

        // Setup scene, camera, and renderer
        let scene = new THREE.Scene();
        let camera = new THREE.PerspectiveCamera(75, window.innerWidth / window.innerHeight, 0.1, 1000);
        let renderer = new THREE.WebGLRenderer();
        renderer.setSize(window.innerWidth, window.innerHeight);
        document.body.appendChild(renderer.domElement);

        // Create stars
        function createStar() {
            let geometry = new THREE.SphereGeometry(0.1, 24, 24);
            let material = new THREE.MeshBasicMaterial({ color: 0xffffff });
            let star = new THREE.Mesh(geometry, material);
            star.position.set(
                (Math.random() - 0.5) * 1000,
                (Math.random() - 0.5) * 1000,
                (Math.random() - 0.5) * 1000
            );
            scene.add(star);

            star.userData = { message: userMessage };

            star.onClick = function () {
                alert(`This star belongs to: ${star.userData.message}`);
            };
        }

        for (let i = 0; i < 500; i++) {
            createStar();
        }

        // Set camera position
        camera.position.z = 1;

        // Animation function
        function animate() {
            requestAnimationFrame(animate);
            camera.position.z += 0.01;
            renderer.render(scene, camera);
        }

        animate();
    </script>
</body>
</html>
