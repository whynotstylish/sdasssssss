<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>SMS Bomber - OLD STUDIO</title>
    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }

        body {
            font-family: 'Arial', sans-serif;
            background: linear-gradient(135deg, #667eea 0%, #764ba2 100%);
            min-height: 100vh;
            display: flex;
            justify-content: center;
            align-items: center;
            padding: 20px;
        }

        .container {
            background: rgba(255, 255, 255, 0.95);
            backdrop-filter: blur(10px);
            border-radius: 20px;
            padding: 40px;
            box-shadow: 0 20px 40px rgba(0, 0, 0, 0.1);
            width: 100%;
            max-width: 450px;
            text-align: center;
            transition: transform 0.3s ease;
        }

        .container:hover {
            transform: translateY(-5px);
        }

        .logo {
            font-size: 2.5em;
            font-weight: bold;
            color: #667eea;
            margin-bottom: 10px;
            text-shadow: 2px 2px 4px rgba(0, 0, 0, 0.1);
        }

        .subtitle {
            color: #666;
            margin-bottom: 30px;
            font-size: 1.1em;
        }

        .form-group {
            margin-bottom: 25px;
            text-align: left;
        }

        .form-group label {
            display: block;
            margin-bottom: 8px;
            color: #333;
            font-weight: 600;
            font-size: 0.95em;
            text-transform: uppercase;
            letter-spacing: 0.5px;
        }

        .form-group input {
            width: 100%;
            padding: 15px;
            border: 2px solid #e1e5e9;
            border-radius: 10px;
            font-size: 16px;
            transition: all 0.3s ease;
            background: #f8f9fa;
        }

        .form-group input:focus {
            outline: none;
            border-color: #667eea;
            background: white;
            box-shadow: 0 0 0 3px rgba(102, 126, 234, 0.1);
        }

        .start-button {
            width: 100%;
            padding: 18px;
            background: linear-gradient(135deg, #667eea 0%, #764ba2 100%);
            color: white;
            border: none;
            border-radius: 12px;
            font-size: 18px;
            font-weight: bold;
            cursor: pointer;
            transition: all 0.3s ease;
            text-transform: uppercase;
            letter-spacing: 1px;
            margin-top: 10px;
        }

        .start-button:hover {
            transform: translateY(-2px);
            box-shadow: 0 10px 25px rgba(102, 126, 234, 0.3);
        }

        .start-button:active {
            transform: translateY(0);
        }

        .start-button:disabled {
            opacity: 0.6;
            cursor: not-allowed;
            transform: none;
        }

        .status {
            margin-top: 20px;
            padding: 15px;
            border-radius: 10px;
            font-weight: 600;
            display: none;
        }

        .status.success {
            background: #d4edda;
            color: #155724;
            border: 1px solid #c3e6cb;
        }

        .status.error {
            background: #f8d7da;
            color: #721c24;
            border: 1px solid #f5c6cb;
        }

        .status.info {
            background: #d1ecf1;
            color: #0c5460;
            border: 1px solid #bee5eb;
        }

        .footer {
            margin-top: 30px;
            padding-top: 20px;
            border-top: 1px solid #e1e5e9;
        }

        .powered-by {
            color: #666;
            font-size: 0.9em;
            margin-bottom: 10px;
        }

        .whatsapp-link {
            display: inline-block;
            background: #25d366;
            color: white;
            padding: 10px 20px;
            border-radius: 25px;
            text-decoration: none;
            font-weight: 600;
            transition: all 0.3s ease;
        }

        .whatsapp-link:hover {
            background: #128c7e;
            transform: translateY(-2px);
        }

        .progress-bar {
            width: 100%;
            height: 6px;
            background: #e1e5e9;
            border-radius: 3px;
            margin-top: 15px;
            overflow: hidden;
            display: none;
        }

        .progress-fill {
            height: 100%;
            background: linear-gradient(90deg, #667eea, #764ba2);
            width: 0%;
            transition: width 0.3s ease;
        }

        @media (max-width: 480px) {
            .container {
                padding: 30px 20px;
                margin: 10px;
            }
            
            .logo {
                font-size: 2em;
            }
        }
    </style>
</head>
<body>
    <div class="container">
        <div class="logo">SMS BOMBER</div>
        <div class="subtitle">Advanced SMS Testing Tool</div>
        
        <form id="bomberForm">
            <div class="form-group">
                <label for="phoneNumber">ENTER YOUR NUMBER</label>
                <input type="tel" id="phoneNumber" placeholder="923001234567" required>
            </div>
            
            <div class="form-group">
                <label for="registerAmount">ENTER AMOUNT OF REGISTER</label>
                <input type="number" id="registerAmount" placeholder="10" min="1" max="100" required>
            </div>
            
            <div class="form-group">
                <label for="delaySeconds">ENTER SEC OF DELAYS</label>
                <input type="number" id="delaySeconds" placeholder="5" min="1" max="60" required>
            </div>
            
            <button type="submit" class="start-button" id="startButton">
                START NOW
            </button>
            
            <div class="progress-bar" id="progressBar">
                <div class="progress-fill" id="progressFill"></div>
            </div>
            
            <div class="status" id="statusMessage"></div>
        </form>
        
        <div class="footer">
            <div class="powered-by">POWERED BY OLD-STUDIO</div>
            <a href="https://whatsapp.com/channel/0029VbAtNf6Likg7MJqCkp2d" class="whatsapp-link" target="_blank">
                📱 Join WhatsApp Channel
            </a>
        </div>
    </div>

    <script>
        const form = document.getElementById('bomberForm');
        const startButton = document.getElementById('startButton');
        const statusMessage = document.getElementById('statusMessage');
        const progressBar = document.getElementById('progressBar');
        const progressFill = document.getElementById('progressFill');

        function showStatus(message, type) {
            statusMessage.textContent = message;
            statusMessage.className = `status ${type}`;
            statusMessage.style.display = 'block';
        }

        function hideStatus() {
            statusMessage.style.display = 'none';
        }

        function updateProgress(percentage) {
            progressFill.style.width = percentage + '%';
        }

        function showProgress() {
            progressBar.style.display = 'block';
        }

        function hideProgress() {
            progressBar.style.display = 'none';
            updateProgress(0);
        }

        async function callAPI(phoneNumber) {
            const apiUrl = `https://shadowscriptz.xyz/shadowapisv4/smsbomberapi.php?number=${phoneNumber}`;
            
            try {
                const response = await fetch(apiUrl, {
                    method: 'GET',
                    mode: 'no-cors' // Handle CORS issues
                });
                
                // Since we're using no-cors, we can't read the response
                // We'll assume success if no error is thrown
                return { success: true };
            } catch (error) {
                console.error('API call failed:', error);
                return { success: false, error: error.message };
            }
        }

        form.addEventListener('submit', async function(e) {
            e.preventDefault();
            
            const phoneNumber = document.getElementById('phoneNumber').value.trim();
            const registerAmount = parseInt(document.getElementById('registerAmount').value);
            const delaySeconds = parseInt(document.getElementById('delaySeconds').value);
            
            // Validation
            if (!phoneNumber || !registerAmount || !delaySeconds) {
                showStatus('Please fill in all fields!', 'error');
                return;
            }
            
            if (phoneNumber.length < 10) {
                showStatus('Please enter a valid phone number!', 'error');
                return;
            }
            
            // Disable button and show progress
            startButton.disabled = true;
            startButton.textContent = 'PROCESSING...';
            hideStatus();
            showProgress();
            
            try {
                showStatus(`Starting SMS bomber for ${phoneNumber}...`, 'info');
                
                for (let i = 0; i < registerAmount; i++) {
                    // Update progress
                    const progress = ((i + 1) / registerAmount) * 100;
                    updateProgress(progress);
                    
                    showStatus(`Sending SMS ${i + 1} of ${registerAmount}...`, 'info');
                    
                    // Call the API
                    const result = await callAPI(phoneNumber);
                    
                    if (!result.success) {
                        showStatus(`Failed at SMS ${i + 1}: ${result.error}`, 'error');
                        break;
                    }
                    
                    // Wait for delay (except for the last iteration)
                    if (i < registerAmount - 1) {
                        await new Promise(resolve => setTimeout(resolve, delaySeconds * 1000));
                    }
                }
                
                updateProgress(100);
                showStatus(`Successfully completed! Sent ${registerAmount} SMS to ${phoneNumber}`, 'success');
                
            } catch (error) {
                showStatus(`Error: ${error.message}`, 'error');
            } finally {
                // Re-enable button
                startButton.disabled = false;
                startButton.textContent = 'START NOW';
                
                // Hide progress after 3 seconds
                setTimeout(() => {
                    hideProgress();
                }, 3000);
            }
        });

        // Auto-format phone number
        document.getElementById('phoneNumber').addEventListener('input', function(e) {
            let value = e.target.value.replace(/\D/g, ''); // Remove non-digits
            e.target.value = value;
        });

        // Limit register amount
        document.getElementById('registerAmount').addEventListener('input', function(e) {
            let value = parseInt(e.target.value);
            if (value > 100) e.target.value = 100;
            if (value < 1) e.target.value = 1;
        });

        // Limit delay seconds
        document.getElementById('delaySeconds').addEventListener('input', function(e) {
            let value = parseInt(e.target.value);
            if (value > 60) e.target.value = 60;
            if (value < 1) e.target.value = 1;
        });
    </script>
</body>
</html>

