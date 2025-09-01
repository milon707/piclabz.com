<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>PicLab Pro - Advanced Online Image Editor</title>
    <link href="https://fonts.googleapis.com/css2?family=Poppins:wght@300;400;500;600;700&display=swap" rel="stylesheet">
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.0/css/all.min.css">
    <style>
        :root {
            --primary: #4361ee;
            --primary-light: #4895ef;
            --secondary: #3f37c9;
            --dark: #1a1a2e;
            --light: #f8f9fa;
            --success: #4cc9f0;
            --warning: #f72585;
            --gray: #6c757d;
            --white: #ffffff;
            --shadow: 0 20px 40px rgba(0,0,0,0.1);
        }
        
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }
        
        body {
            font-family: 'Poppins', sans-serif;
            line-height: 1.6;
            color: var(--dark);
            background-color: var(--light);
            overflow-x: hidden;
        }
        
        .container {
            max-width: 1200px;
            margin: 0 auto;
            padding: 0 20px;
        }
        
        /* 3D Tool Cards Section */
        .editing-tools {
            padding: 6rem 1rem;
            text-align: center;
            position: relative;
            overflow: hidden;
        }
        
        .editing-tools::before {
            content: '';
            position: absolute;
            top: 0;
            left: 0;
            width: 100%;
            height: 100%;
            background: linear-gradient(135deg, rgba(67, 97, 238, 0.03) 0%, rgba(63, 55, 201, 0.03) 100%);
            z-index: -1;
        }
        
        .editing-tools h1 {
            font-size: 3rem;
            font-weight: 700;
            margin-bottom: 1.5rem;
            color: var(--dark);
            background: linear-gradient(90deg, #4361ee, #3f37c9);
            -webkit-background-clip: text;
            -webkit-text-fill-color: transparent;
            position: relative;
            display: inline-block;
        }
        
        .editing-tools h1::after {
            content: '';
            position: absolute;
            bottom: -10px;
            left: 50%;
            transform: translateX(-50%);
            width: 80px;
            height: 4px;
            background: linear-gradient(90deg, #4361ee, #3f37c9);
            border-radius: 2px;
        }
        
        .editing-tools p {
            font-size: 1.2rem;
            max-width: 700px;
            margin: 0 auto 3rem;
            color: var(--gray);
        }
        
        .services-grid {
            display: grid;
            grid-template-columns: repeat(2, 1fr);
            gap: 2rem;
            max-width: 1000px;
            margin: 0 auto;
            perspective: 1000px;
        }
        
        .service-card {
            background: var(--white);
            border-radius: 16px;
            padding: 2.5rem 2rem;
            text-align: center;
            box-shadow: var(--shadow);
            transition: all 0.5s cubic-bezier(0.175, 0.885, 0.32, 1.275);
            transform-style: preserve-3d;
            position: relative;
            overflow: hidden;
            border: 1px solid rgba(67, 97, 238, 0.1);
            height: 100%;
            display: block;
            text-decoration: none;
            color: inherit;
        }
        
        .service-card::before {
            content: '';
            position: absolute;
            top: 0;
            left: 0;
            width: 100%;
            height: 5px;
            background: linear-gradient(90deg, #4361ee, #3f37c9);
        }
        
        .service-card:hover {
            transform: translateY(-10px) rotateX(5deg);
            box-shadow: 0 30px 50px rgba(67, 97, 238, 0.2);
        }
        
        .icon-container {
            position: relative;
            width: 100px;
            height: 100px;
            margin: 0 auto 1.5rem;
            perspective: 1000px;
        }
        
        .icon {
            width: 100%;
            height: 100%;
            border-radius: 50%;
            display: flex;
            align-items: center;
            justify-content: center;
            font-size: 2.5rem;
            color: var(--white);
            position: relative;
            transform-style: preserve-3d;
            transition: all 0.5s ease;
            box-shadow: 0 10px 20px rgba(0,0,0,0.1);
        }
        
        .icon::after {
            content: '';
            position: absolute;
            top: 0;
            left: 0;
            width: 100%;
            height: 100%;
            border-radius: 50%;
            background: inherit;
            transform: translateZ(-20px);
            filter: brightness(0.8);
        }
        
        .service-card:hover .icon {
            transform: rotateY(180deg);
        }
        
        .crop {
            background: linear-gradient(45deg, #4cc9f0, #4895ef);
        }
        
        .compress {
            background: linear-gradient(45deg, #38b000, #70e000);
        }
        
        .convert {
            background: linear-gradient(45deg, #ff9e00, #ff9100);
        }
        
        .watermark {
            background: linear-gradient(45deg, #7209b7, #560bad);
        }
        
        .service-card h3 {
            font-size: 1.5rem;
            margin-bottom: 1rem;
            position: relative;
            display: inline-block;
        }
        
        .service-card h3::after {
            content: '';
            position: absolute;
            bottom: -8px;
            left: 50%;
            transform: translateX(-50%);
            width: 40px;
            height: 3px;
            background: var(--primary);
            border-radius: 2px;
        }
        
        .service-card p {
            color: var(--gray);
            margin-bottom: 1.5rem;
            font-size: 1rem;
            line-height: 1.6;
        }
        
        .btn {
            display: inline-block;
            padding: 0.8rem 2rem;
            border-radius: 50px;
            font-weight: 600;
            text-decoration: none;
            transition: all 0.3s ease;
            border: none;
            cursor: pointer;
            position: relative;
            overflow: hidden;
        }
        
        .btn-primary {
            background: linear-gradient(90deg, #4361ee, #3f37c9);
            color: var(--white);
            box-shadow: 0 5px 15px rgba(67, 97, 238, 0.3);
        }
        
        .btn-primary:hover {
            transform: translateY(-3px);
            box-shadow: 0 8px 20px rgba(67, 97, 238, 0.4);
        }
        
        .btn-primary::before {
            content: '';
            position: absolute;
            top: 0;
            left: -100%;
            width: 100%;
            height: 100%;
            background: linear-gradient(90deg, transparent, rgba(255,255,255,0.2), transparent);
            transition: 0.5s;
        }
        
        .btn-primary:hover::before {
            left: 100%;
        }
        
        /* How It Works Section */
        .how-it-works {
            padding: 6rem 0;
            background-color: var(--white);
            position: relative;
        }
        
        .how-it-works::before {
            content: '';
            position: absolute;
            top: 0;
            left: 0;
            width: 100%;
            height: 100%;
            background: url('data:image/svg+xml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHdpZHRoPSIxMDAlIiBoZWlnaHQ9IjEwMCUiPjxkZWZzPjxwYXR0ZXJuIGlkPSJwYXR0ZXJuIiB3aWR0aD0iNDAiIGhlaWdodD0iNDAiIHBhdHRlcm5Vbml0cz0idXNlclNwYWNlT25Vc2UiIHBhdHRlcm5UcmFuc2Zvcm09InJvdGF0ZSg0NSkiPjxyZWN0IHdpZHRoPSIyMCIgaGVpZ2h0PSIyMCIgZmlsbD0icmdiYSg2Nyw5NywyMzgsMC4wNSkiLz48L3BhdHRlcm4+PC9kZWZzPjxyZWN0IHdpZHRoPSIxMDAlIiBoZWlnaHQ9IjEwMCUiIGZpbGw9InVybCgjcGF0dGVybikiLz48L3N2Zz4=');
            opacity: 0.5;
            z-index: 0;
        }
        
        .how-it-works h2 {
            text-align: center;
            font-size: 2.5rem;
            margin-bottom: 3rem;
            color: var(--dark);
            position: relative;
            z-index: 1;
        }
        
        .steps {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
            gap: 3rem;
            max-width: 1000px;
            margin: 0 auto;
            position: relative;
            z-index: 1;
        }
        
        .step {
            text-align: center;
            padding: 2.5rem 2rem;
            background: var(--white);
            border-radius: 16px;
            box-shadow: var(--shadow);
            transition: all 0.3s ease;
            position: relative;
            overflow: hidden;
            border: 1px solid rgba(67, 97, 238, 0.1);
        }
        
        .step:hover {
            transform: translateY(-10px);
            box-shadow: 0 25px 50px rgba(67, 97, 238, 0.15);
        }
        
        .step-number {
            width: 60px;
            height: 60px;
            margin: 0 auto 1.5rem;
            border-radius: 50%;
            display: flex;
            align-items: center;
            justify-content: center;
            font-size: 1.5rem;
            font-weight: 700;
            color: var(--white);
            background: linear-gradient(135deg, #4361ee, #3f37c9);
            box-shadow: 0 10px 20px rgba(67, 97, 238, 0.2);
            position: relative;
        }
        
        .step-number::after {
            content: '';
            position: absolute;
            top: -5px;
            left: -5px;
            right: -5px;
            bottom: -5px;
            border-radius: 50%;
            border: 2px dashed rgba(67, 97, 238, 0.3);
            animation: rotate 15s linear infinite;
        }
        
        @keyframes rotate {
            0% { transform: rotate(0deg); }
            100% { transform: rotate(360deg); }
        }
        
        .step i {
            font-size: 2.5rem;
            margin-bottom: 1.5rem;
            color: var(--primary);
            background: rgba(67, 97, 238, 0.1);
            width: 80px;
            height: 80px;
            line-height: 80px;
            border-radius: 50%;
            display: inline-block;
        }
        
        .step h3 {
            font-size: 1.5rem;
            margin-bottom: 1rem;
            color: var(--dark);
        }
        
        .step p {
            color: var(--gray);
            font-size: 1rem;
            line-height: 1.6;
        }
        
        /* Why Our Tools Stand Out Section */
        .stand-out {
            padding: 6rem 0;
            background: linear-gradient(135deg, #f8f9fa 0%, #e9ecef 100%);
            position: relative;
        }
        
        .stand-out h2 {
            text-align: center;
            font-size: 2.5rem;
            margin-bottom: 3rem;
            color: var(--dark);
        }
        
        .features {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
            gap: 3rem;
            max-width: 1000px;
            margin: 0 auto;
        }
        
        .feature {
            text-align: center;
            padding: 2.5rem 2rem;
            background: var(--white);
            border-radius: 16px;
            box-shadow: var(--shadow);
            transition: all 0.3s ease;
            position: relative;
            overflow: hidden;
            border: 1px solid rgba(67, 97, 238, 0.1);
        }
        
        .feature:hover {
            transform: translateY(-10px);
            box-shadow: 0 25px 50px rgba(67, 97, 238, 0.15);
        }
        
        .feature-icon {
            width: 100px;
            height: 100px;
            margin: 0 auto 1.5rem;
            position: relative;
        }
        
        .feature-icon i {
            font-size: 2.5rem;
            color: var(--white);
            background: linear-gradient(135deg, #4361ee, #3f37c9);
            width: 80px;
            height: 80px;
            line-height: 80px;
            border-radius: 50%;
            display: inline-block;
            position: relative;
            z-index: 1;
            box-shadow: 0 10px 20px rgba(67, 97, 238, 0.2);
        }
        
        .feature-icon::before {
            content: '';
            position: absolute;
            top: 0;
            left: 50%;
            transform: translateX(-50%);
            width: 60px;
            height: 60px;
            background: rgba(67, 97, 238, 0.1);
            border-radius: 50%;
            animation: pulse 2s infinite;
        }
        
        @keyframes pulse {
            0% { transform: translateX(-50%) scale(1); opacity: 1; }
            100% { transform: translateX(-50%) scale(1.5); opacity: 0; }
        }
        
        .feature h3 {
            font-size: 1.5rem;
            margin-bottom: 1rem;
            color: var(--dark);
        }
        
        .feature p {
            color: var(--gray);
            font-size: 1rem;
            line-height: 1.6;
        }
        
        /* Client Reviews Section */
        .client-reviews {
            padding: 6rem 0;
            background: linear-gradient(135deg, #4361ee 0%, #3f37c9 100%);
            color: var(--white);
            position: relative;
            overflow: hidden;
        }
        
        .client-reviews::before {
            content: '';
            position: absolute;
            top: 0;
            left: 0;
            width: 100%;
            height: 100%;
            background: url('data:image/svg+xml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHdpZHRoPSIxMDAlIiBoZWlnaHQ9IjEwMCUiPjxkZWZzPjxwYXR0ZXJuIGlkPSJwYXR0ZXJuIiB3aWR0aD0iNDAiIGhlaWdodD0iNDAiIHBhdHRlcm5Vbml0cz0idXNlclNwYWNlT25Vc2UiIHBhdHRlcm5UcmFuc2Zvcm09InJvdGF0ZSg0NSkiPjxyZWN0IHdpZHRoPSIyMCIgaGVpZ2h0PSIyMCIgZmlsbD0icmdiYSgyNTUsMjU1LDI1NSwwLjA1KSIvPjwvcGF0dGVybj48L2RlZnM+PHJlY3Qgd2lkdGg9IjEwMCUiIGhlaWdodD0iMTAwJSIgZmlsbD0idXJsKCNwYXR0ZXJuKSIvPjwvc3ZnPg==');
            opacity: 0.3;
        }
        
        .client-reviews h2 {
            text-align: center;
            font-size: 2.5rem;
            margin-bottom: 3rem;
            position: relative;
        }
        
        .reviews {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
            gap: 2rem;
            max-width: 1000px;
            margin: 0 auto;
            position: relative;
        }
        
        .review {
            background: rgba(255, 255, 255, 0.1);
            backdrop-filter: blur(10px);
            border-radius: 16px;
            padding: 2rem;
            box-shadow: 0 10px 30px rgba(0, 0, 0, 0.1);
            transition: all 0.3s ease;
            border: 1px solid rgba(255, 255, 255, 0.2);
        }
        
        .review:hover {
            transform: translateY(-10px);
            background: rgba(255, 255, 255, 0.15);
        }
        
        .review-text {
            font-style: italic;
            margin-bottom: 1.5rem;
            position: relative;
            font-size: 1rem;
            line-height: 1.6;
        }
        
        .review-text::before,
        .review-text::after {
            content: '"';
            font-size: 3rem;
            color: rgba(255, 255, 255, 0.2);
            position: absolute;
            line-height: 1;
        }
        
        .review-text::before {
            top: -1rem;
            left: -1rem;
        }
        
        .review-text::after {
            bottom: -2rem;
            right: -1rem;
        }
        
        .reviewer {
            display: flex;
            align-items: center;
            margin-top: 2rem;
        }
        
        .reviewer img {
            width: 60px;
            height: 60px;
            border-radius: 50%;
            object-fit: cover;
            margin-right: 1rem;
            border: 3px solid rgba(255, 255, 255, 0.3);
        }
        
        .reviewer-info h4 {
            font-size: 1.1rem;
            margin-bottom: 0.3rem;
        }
        
        .reviewer-info p {
            font-size: 0.9rem;
            opacity: 0.8;
        }
        
        /* Responsive */
        @media (max-width: 768px) {
            .editing-tools h1, 
            .how-it-works h2, 
            .stand-out h2, 
            .client-reviews h2 {
                font-size: 2rem;
            }
            
            .editing-tools, 
            .how-it-works, 
            .stand-out, 
            .client-reviews {
                padding: 4rem 0;
            }
            
            .services-grid {
                grid-template-columns: 1fr;
            }
            
            .steps, 
            .features, 
            .reviews {
                grid-template-columns: 1fr;
            }
        }
    </style>
</head>
<body>

<?php include('header/header.php'); ?>

    <main>
        <!-- 3D Tool Cards Section -->
        <section class="editing-tools">
            <div class="container">
                <h1>Advanced Image Editing Toolkit</h1>
                <p>Professional-grade tools for all your image editing needs with stunning 3D effects</p>
                
                <div class="services-grid">
                    <!-- First Row -->
                    <a href="crop-resize.php" class="service-card">
                        <div class="icon-container">
                            <div class="icon crop">
                                <i class="fas fa-crop-alt"></i>
                            </div>
                        </div>
                        <h3>Crop & Resize</h3>
                        <p>Precisely crop and resize your images for any platform with pixel-perfect accuracy</p>
                        <span class="btn btn-primary">Use Tool</span>
                    </a>
                    
                    <a href="compressor.php" class="service-card">
                        <div class="icon-container">
                            <div class="icon compress">
                                <i class="fas fa-compress-alt"></i>
                            </div>
                        </div>
                        <h3>Image Compressor</h3>
                        <p>Reduce file size without noticeable quality loss for faster loading websites</p>
                        <span class="btn btn-primary">Use Tool</span>
                    </a>
                    
                    <!-- Second Row -->
                    <a href="image-format-converter.php" class="service-card">
                        <div class="icon-container">
                            <div class="icon convert">
                                <i class="fas fa-exchange-alt"></i>
                            </div>
                        </div>
                        <h3>Format Converter</h3>
                        <p>Convert between JPG, PNG, WEBP and other popular formats effortlessly</p>
                        <span class="btn btn-primary">Use Tool</span>
                    </a>
                    
                    <a href="add_watermark.php" class="service-card">
                        <div class="icon-container">
                            <div class="icon watermark">
                                <i class="fas fa-stamp"></i>
                            </div>
                        </div>
                        <h3>Watermark Tool</h3>
                        <p>Protect your creative work with customizable text or image watermarks</p>
                        <span class="btn btn-primary">Use Tool</span>
                    </a>
                </div>
            </div>
        </section>

        <!-- How It Works Section -->
        <section class="how-it-works">
            <div class="container">
                <h2>How It Works</h2>
                <div class="steps">
                    <div class="step">
                        <div class="step-number">1</div>
                        <i class="fas fa-cloud-upload-alt"></i>
                        <h3>Upload Your Image</h3>
                        <p>Simply drag & drop your image file or select from your device. We support all major image formats.</p>
                    </div>
                    <div class="step">
                        <div class="step-number">2</div>
                        <i class="fas fa-sliders-h"></i>
                        <h3>Edit with Precision</h3>
                        <p>Use our intuitive tools to crop, resize, compress or convert your image exactly how you need it.</p>
                    </div>
                    <div class="step">
                        <div class="step-number">3</div>
                        <i class="fas fa-file-download"></i>
                        <h3>Download & Share</h3>
                        <p>Save your edited image in perfect quality or share directly to social media platforms.</p>
                    </div>
                </div>
            </div>
        </section>

        <!-- Why Our Tools Stand Out Section -->
        <section class="stand-out">
            <div class="container">
                <h2>Why Our Tools Stand Out</h2>
                <div class="features">
                    <div class="feature">
                        <div class="feature-icon">
                            <i class="fas fa-bolt"></i>
                        </div>
                        <h3>Blazing Fast Processing</h3>
                        <p>Our cloud-powered infrastructure processes your images in seconds, no matter the size.</p>
                    </div>
                    <div class="feature">
                        <div class="feature-icon">
                            <i class="fas fa-lock-open"></i>
                        </div>
                        <h3>100% Free Forever</h3>
                        <p>No hidden charges, no watermarks, no registration required. Truly free for everyone.</p>
                    </div>
                    <div class="feature">
                        <div class="feature-icon">
                            <i class="fas fa-shield-alt"></i>
                        </div>
                        <h3>Military-Grade Security</h3>
                        <p>Your images are automatically deleted after processing. We never store your files.</p>
                    </div>
                </div>
            </div>
        </section>

        <!-- Client Reviews Section -->
        <section class="client-reviews">
            <div class="container">
                <h2>What Our Clients Say</h2>
                <div class="reviews">
                    <div class="review">
                        <p class="review-text">This is hands down the best online image editor I've used. The quality is exceptional and it's completely free. I use it daily for my e-commerce store.</p>
                        <div class="reviewer">
                            <img src="https://randomuser.me/api/portraits/women/44.jpg" alt="Sarah Johnson">
                            <div class="reviewer-info">
                                <h4>Sarah Johnson</h4>
                                <p>E-commerce Entrepreneur</p>
                            </div>
                        </div>
                    </div>
                    <div class="review">
                        <p class="review-text">As a photographer, I need precise editing tools. PicLab Pro gives me professional results without expensive software. The watermark tool is perfect!</p>
                        <div class="reviewer">
                            <img src="https://randomuser.me/api/portraits/men/32.jpg" alt="Michael Chen">
                            <div class="reviewer-info">
                                <h4>Michael Chen</h4>
                                <p>Professional Photographer</p>
                            </div>
                        </div>
                    </div>
                    <div class="review">
                        <p class="review-text">The image compressor saved our company thousands in bandwidth costs. Fast, easy to use, and the quality remains excellent even at 70% compression.</p>
                        <div class="reviewer">
                            <img src="https://randomuser.me/api/portraits/women/68.jpg" alt="Emma Rodriguez">
                            <div class="reviewer-info">
                                <h4>Emma Rodriguez</h4>
                                <p>Web Development Team Lead</p>
                            </div>
                        </div>
                    </div>
                </div>
            </div>
        </section>
    </main>

<?php include('footer/footer.php'); ?>

    <script>
        // Add hover effects to service cards
        document.querySelectorAll('.service-card').forEach(card => {
            card.addEventListener('mouseenter', () => {
                card.style.transform = 'translateY(-10px) rotateX(5deg)';
                card.style.boxShadow = '0 30px 50px rgba(67, 97, 238, 0.2)';
            });
            
            card.addEventListener('mouseleave', () => {
                card.style.transform = '';
                card.style.boxShadow = 'var(--shadow)';
            });
        });
    </script>
</body>
</html>