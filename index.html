<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>AgentCodr - Transformation Animation</title>
    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }

        body {
            font-family: 'Inter', -apple-system, BlinkMacSystemFont, 'Segoe UI', sans-serif;
            background: linear-gradient(135deg, #181926 0%, #1e2030 100%);
            min-height: 100vh;
            display: flex;
            justify-content: center;
            align-items: center;
            color: #cad3f5;
            overflow: hidden;
        }

        .transformation-container {
            width: 100%;
            max-width: 1200px;
            padding: 60px;
            position: relative;
        }

        /* Transformation stages */
        .stage {
            position: absolute;
            width: 100%;
            height: 100%;
            display: flex;
            align-items: center;
            justify-content: center;
            opacity: 0;
            transition: all 1.5s cubic-bezier(0.4, 0, 0.2, 1);
        }

        .stage.active {
            opacity: 1;
        }

        /* Stage 1: Chaos */
        .chaos-stage {
            animation: chaosIn 2s ease-out;
        }

        @keyframes chaosIn {
            0% { transform: scale(0.8) rotate(-5deg); opacity: 0; }
            100% { transform: scale(1) rotate(0deg); opacity: 1; }
        }

        .chaos-elements {
            position: relative;
            width: 600px;
            height: 400px;
        }

        .chaos-item {
            position: absolute;
            padding: 15px 25px;
            background: rgba(49, 50, 68, 0.8);
            border: 1px solid rgba(203, 166, 247, 0.3);
            border-radius: 8px;
            color: #a6adc8;
            font-size: 14px;
            animation: float-chaos 4s ease-in-out infinite;
        }

        @keyframes float-chaos {
            0%, 100% { transform: translateY(0) rotate(-2deg); }
            50% { transform: translateY(-20px) rotate(2deg); }
        }

        /* Chaos items with brand colors */
        .chaos-item:nth-child(1) { 
            top: 20%; 
            left: 10%; 
            animation-delay: 0s; 
            background: rgba(203, 166, 247, 0.1);
            border-color: rgba(203, 166, 247, 0.4);
        }
        .chaos-item:nth-child(2) { 
            top: 50%; 
            right: 15%; 
            animation-delay: 0.5s;
            background: rgba(137, 180, 250, 0.1);
            border-color: rgba(137, 180, 250, 0.4);
        }
        .chaos-item:nth-child(3) { 
            bottom: 30%; 
            left: 20%; 
            animation-delay: 1s;
            background: rgba(74, 222, 128, 0.1);
            border-color: rgba(74, 222, 128, 0.4);
        }
        .chaos-item:nth-child(4) { 
            top: 10%; 
            right: 25%; 
            animation-delay: 1.5s;
            background: rgba(245, 169, 127, 0.1);
            border-color: rgba(245, 169, 127, 0.4);
        }

        /* Stage 2: Robot Arrival */
        .robot-stage {
            flex-direction: column;
            gap: 30px;
        }

        .robot-entrance {
            animation: robotArrive 2s ease-out;
        }

        @keyframes robotArrive {
            0% { 
                transform: scale(0) rotate(720deg); 
                filter: brightness(2) blur(10px);
            }
            50% { 
                transform: scale(1.2) rotate(360deg); 
                filter: brightness(1.5) blur(5px);
            }
            100% { 
                transform: scale(1) rotate(0deg); 
                filter: brightness(1) blur(0);
            }
        }

        .robot-container {
            width: 200px;
            height: 200px;
            position: relative;
        }

        .robot-image {
            width: 100%;
            height: 100%;
            border-radius: 24px;
            position: absolute;
            top: 0;
            left: 0;
            transition: all 0.3s ease;
        }

        .robot-image.open {
            opacity: 1;
        }

        .robot-image.wink {
            opacity: 0;
        }

        .robot-container.winking .robot-image.open {
            opacity: 0;
        }

        .robot-container.winking .robot-image.wink {
            opacity: 1;
        }

        .robot-container.processing {
            animation: process 1s ease-in-out;
        }

        @keyframes process {
            0%, 100% { transform: scale(1); }
            25% { transform: scale(1.1) rotate(-5deg); }
            50% { transform: scale(1.15); }
            75% { transform: scale(1.1) rotate(5deg); }
        }

        /* Energy waves */
        .energy-wave {
            position: absolute;
            width: 300px;
            height: 300px;
            border-radius: 50%;
            border: 2px solid;
            top: 50%;
            left: 50%;
            transform: translate(-50%, -50%);
            opacity: 0;
        }

        .energy-wave.pulse {
            animation: energyPulse 2s ease-out;
        }

        @keyframes energyPulse {
            0% {
                width: 200px;
                height: 200px;
                opacity: 1;
                border-color: #cba6f7;
            }
            50% {
                border-color: #89b4fa;
            }
            100% {
                width: 600px;
                height: 600px;
                opacity: 0;
                border-color: #4ade80;
            }
        }

        /* Stage 3: Transformation */
        .transform-stage {
            width: 100%;
        }

        .transform-visual {
            display: flex;
            align-items: center;
            justify-content: center;
            gap: 50px;
        }

        .before-box, .after-box {
            padding: 30px;
            border-radius: 16px;
            width: 300px;
            transition: all 1s ease;
        }

        .before-box {
            background: rgba(49, 50, 68, 0.6);
            border: 2px dashed rgba(203, 166, 247, 0.3);
            transform: translateX(-100px);
            opacity: 0;
        }

        .before-box.show {
            transform: translateX(0);
            opacity: 1;
        }

        .after-box {
            background: linear-gradient(135deg, rgba(74, 222, 128, 0.1), rgba(137, 180, 250, 0.1));
            border: 2px solid rgba(74, 222, 128, 0.5);
            transform: translateX(100px);
            opacity: 0;
        }

        .after-box.show {
            transform: translateX(0);
            opacity: 1;
        }

        .transform-arrow {
            font-size: 3rem;
            color: #cba6f7;
            animation: arrowPulse 2s ease-in-out infinite;
        }

        @keyframes arrowPulse {
            0%, 100% { transform: scale(1) translateX(0); }
            50% { transform: scale(1.2) translateX(10px); }
        }

        /* Data particles */
        .particle-system {
            position: absolute;
            width: 100%;
            height: 100%;
            pointer-events: none;
        }

        .particle {
            position: absolute;
            width: 4px;
            height: 4px;
            background: #89b4fa;
            border-radius: 50%;
            opacity: 0;
        }

        .particle.flow {
            animation: particleFlow 3s ease-out;
        }

        @keyframes particleFlow {
            0% {
                transform: translate(0, 0) scale(0);
                opacity: 1;
            }
            50% {
                transform: translate(var(--tx), var(--ty)) scale(1);
                opacity: 0.8;
            }
            100% {
                transform: translate(calc(var(--tx) * 2), calc(var(--ty) * 2)) scale(0);
                opacity: 0;
            }
        }

        /* Success message */
        .success-message {
            text-align: center;
            opacity: 0;
            transform: translateY(20px);
            transition: all 1s ease;
        }

        .success-message.show {
            opacity: 1;
            transform: translateY(0);
        }

        .success-title {
            font-size: 3rem;
            font-weight: 700;
            background: linear-gradient(135deg, #4ade80 0%, #89b4fa 50%, #cba6f7 100%);
            -webkit-background-clip: text;
            background-clip: text;
            -webkit-text-fill-color: transparent;
            margin-bottom: 20px;
            animation: shimmer 3s ease-in-out infinite;
        }

        @keyframes shimmer {
            0%, 100% { filter: brightness(1) hue-rotate(0deg); }
            50% { filter: brightness(1.3) hue-rotate(10deg); }
        }

        /* Control buttons */
        .controls {
            position: fixed;
            bottom: 30px;
            left: 50%;
            transform: translateX(-50%);
            display: flex;
            gap: 15px;
            z-index: 1000;
        }

        .control-btn {
            padding: 12px 24px;
            background: linear-gradient(135deg, #cba6f7 0%, #89b4fa 100%);
            border: none;
            border-radius: 10px;
            color: white;
            font-weight: 600;
            cursor: pointer;
            transition: all 0.3s;
            font-size: 14px;
        }

        .control-btn:hover {
            transform: translateY(-2px);
            box-shadow: 0 5px 20px rgba(203, 166, 247, 0.5);
        }

        .control-btn:active {
            transform: translateY(0);
        }

        /* Loading bar */
        .loading-bar {
            position: fixed;
            top: 0;
            left: 0;
            width: 100%;
            height: 4px;
            background: rgba(30, 32, 48, 0.5);
            overflow: hidden;
        }

        .loading-progress {
            height: 100%;
            width: 0%;
            background: linear-gradient(90deg, #cba6f7, #89b4fa, #4ade80);
            transition: width 0.3s ease;
            box-shadow: 0 0 10px rgba(74, 222, 128, 0.5);
        }
    </style>
</head>
<body>
    <div class="loading-bar">
        <div class="loading-progress" id="progress"></div>
    </div>

    <div class="transformation-container">
        <!-- Stage 1: Business Chaos -->
        <div class="stage chaos-stage" id="stage1">
            <div class="chaos-elements">
                <div class="chaos-item">📊 Disconnected data</div>
                <div class="chaos-item">⏰ Manual processes</div>
                <div class="chaos-item">🔄 Repetitive tasks</div>
                <div class="chaos-item">📈 Scaling challenges</div>
            </div>
        </div>

        <!-- Stage 2: Robot Arrives -->
        <div class="stage robot-stage" id="stage2">
            <div class="robot-entrance">
                <div class="robot-container" id="robotContainer">
                    <img src="robot-open.png" class="robot-image open" alt="Robot">
                    <img src="robot-wink.png" class="robot-image wink" alt="Robot Winking">
                    <div class="energy-wave" id="wave1"></div>
                    <div class="energy-wave" id="wave2"></div>
                </div>
            </div>
            <h2 style="color: #b8c0e0; font-size: 1.5rem; text-align: center; opacity: 0; animation: fadeIn 1s ease 1s forwards;">
                AI that learns your business
            </h2>
        </div>

        <!-- Stage 3: Transformation Complete -->
        <div class="stage transform-stage" id="stage3">
            <div class="transform-visual">
                <div class="before-box" id="beforeBox">
                    <h3 style="color: #cba6f7; margin-bottom: 15px;">Before</h3>
                    <ul style="list-style: none; padding: 0; color: #a6adc8;">
                        <li>⚡ Manual workflows</li>
                        <li>⚡ Data silos</li>
                        <li>⚡ Slow processes</li>
                    </ul>
                </div>
                <div class="transform-arrow">→</div>
                <div class="after-box" id="afterBox">
                    <h3 style="color: #4ade80; margin-bottom: 15px;">After AgentCodr</h3>
                    <ul style="list-style: none; padding: 0; color: #b8c0e0;">
                        <li>✅ Automated systems</li>
                        <li>✅ Unified intelligence</li>
                        <li>✅ 12X faster execution</li>
                    </ul>
                </div>
            </div>
            <div class="success-message" id="successMsg">
                <h1 class="success-title">Transformation Complete</h1>
                <p style="color: #b8c0e0; font-size: 1.2rem;">Your business, powered by AI</p>
            </div>
        </div>

        <div class="particle-system" id="particles"></div>
    </div>

    <div class="controls">
        <button class="control-btn" onclick="startTransformation()">Watch Transformation</button>
        <button class="control-btn" onclick="resetAnimation()">Reset</button>
    </div>

    <style>
        @keyframes fadeIn {
            to { opacity: 1; }
        }
    </style>

    <script>
        let currentStage = 0;
        const stages = ['stage1', 'stage2', 'stage3'];
        
        function updateProgress(percent) {
            document.getElementById('progress').style.width = percent + '%';
        }
        
        function showStage(stageNum) {
            stages.forEach((stage, index) => {
                const element = document.getElementById(stage);
                if (index === stageNum) {
                    element.classList.add('active');
                } else {
                    element.classList.remove('active');
                }
            });
        }
        
        function createParticles() {
            const container = document.getElementById('particles');
            container.innerHTML = '';
            
            for (let i = 0; i < 30; i++) {
                setTimeout(() => {
                    const particle = document.createElement('div');
                    particle.className = 'particle';
                    particle.style.left = Math.random() * 100 + '%';
                    particle.style.top = Math.random() * 100 + '%';
                    particle.style.setProperty('--tx', (Math.random() - 0.5) * 200 + 'px');
                    particle.style.setProperty('--ty', (Math.random() - 0.5) * 200 + 'px');
                    particle.style.background = ['#cba6f7', '#89b4fa', '#4ade80'][Math.floor(Math.random() * 3)];
                    container.appendChild(particle);
                    particle.classList.add('flow');
                    
                    setTimeout(() => particle.remove(), 3000);
                }, i * 100);
            }
        }
        
        function startTransformation() {
            currentStage = 0;
            updateProgress(0);
            showStage(0);
            
            // Stage 1: Show chaos
            setTimeout(() => {
                updateProgress(25);
            }, 1000);
            
            // Stage 2: Robot arrives
            setTimeout(() => {
                showStage(1);
                updateProgress(50);
                
                // Robot processing animation
                const robot = document.getElementById('robotContainer');
                setTimeout(() => {
                    robot.classList.add('processing');
                    robot.classList.add('winking');
                    
                    // Energy waves
                    document.getElementById('wave1').classList.add('pulse');
                    setTimeout(() => {
                        document.getElementById('wave2').classList.add('pulse');
                    }, 500);
                    
                    setTimeout(() => {
                        robot.classList.remove('winking');
                        robot.classList.remove('processing');
                    }, 1000);
                }, 1000);
                
                createParticles();
            }, 3000);
            
            // Stage 3: Transformation complete
            setTimeout(() => {
                showStage(2);
                updateProgress(75);
                
                setTimeout(() => {
                    document.getElementById('beforeBox').classList.add('show');
                    setTimeout(() => {
                        document.getElementById('afterBox').classList.add('show');
                        updateProgress(90);
                        setTimeout(() => {
                            document.getElementById('successMsg').classList.add('show');
                            updateProgress(100);
                            createParticles();
                        }, 1000);
                    }, 500);
                }, 500);
            }, 7000);
        }
        
        function resetAnimation() {
            currentStage = 0;
            updateProgress(0);
            showStage(0);
            
            // Reset all animations
            document.getElementById('beforeBox').classList.remove('show');
            document.getElementById('afterBox').classList.remove('show');
            document.getElementById('successMsg').classList.remove('show');
            document.getElementById('wave1').classList.remove('pulse');
            document.getElementById('wave2').classList.remove('pulse');
            document.getElementById('robotContainer').classList.remove('processing', 'winking');
        }
        
        // Initialize
        document.addEventListener('DOMContentLoaded', () => {
            showStage(0);
        });
    </script>
</body>
</html>
