<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>AutoImageCaptioning</title>
    <style>
        body { font-family: Arial, sans-serif; line-height: 1.6; background-color: #f8f9fa; padding: 20px; color: #333; }
        h1, h2 { color: #2c3e50; }
        code { background-color: #eef; padding: 3px 6px; border-radius: 4px; }
        .container { max-width: 800px; margin: auto; background: white; padding: 20px; border-radius: 8px; box-shadow: 0 0 10px rgba(0,0,0,0.1); }
        .section { margin-bottom: 20px; }
        .commands { background: #272822; color: #f8f8f2; padding: 10px; border-radius: 5px; overflow-x: auto; }
    </style>
</head>
<body>

<div class="container">
    <h1>🖼️ AutoImageCaptioning</h1>
    <p><strong>AutoImageCaptioning</strong> is a lightweight image captioning system that generates textual descriptions for images using the <code>BLIP</code> model.</p>

    <div class="section">
        <h2>🚀 Features</h2>
        <ul>
            <li>✅ <strong>Automatic Caption Generation</strong> – Generate meaningful captions for images.</li>
            <li>✅ <strong>BLIP Model</strong> – Uses <code>Salesforce/blip-image-captioning-base</code> for high-quality captions.</li>
            <li>✅ <strong>Optimized for Efficiency</strong> – Low computation, minimal storage usage.</li>
            <li>✅ <strong>Beginner-Friendly</strong> – Easy setup & integration.</li>
        </ul>
    </div>

    <div class="section">
        <h2>🛠️ Installation</h2>
        <p>To install required dependencies, run:</p>
        <div class="commands">
            <code>pip install torch torchvision transformers pillow</code>
        </div>
    </div>

    <div class="section">
        <h2>📸 Usage</h2>
        <p><strong>1️⃣ Import & Load the Model</strong></p>
        <div class="commands">
            <code>from caption_generator import generate_caption</code>
        </div>
        <p><strong>2️⃣ Generate a Caption for an Image</strong></p>
        <div class="commands">
            <code>caption = generate_caption("your_image.jpg")</code><br>
            <code>print("Generated Caption:", caption)</code>
        </div>
    </div>

    <div class="section">
        <h2>📂 Project Structure</h2>
        <ul>
            <li>📜 <strong>caption_generator.py</strong> – Core script for caption generation</li>
            <li>🖼️ <strong>test.jpg</strong> – Sample image</li>
            <li>📖 <strong>README.md</strong> – Project documentation</li>
        </ul>
    </div>

    <div class="section">
        <h2>🎯 How It Works</h2>
        <ol>
            <li>📷 Load and preprocess the image.</li>
            <li>🧠 Pass it through the BLIP model to generate a caption.</li>
            <li>📝 Output the caption for use.</li>
        </ol>
    </div>

    <div class="section">
        <h2>🏗️ Future Improvements</h2>
        <ul>
            <li>🔹 Optimize model for lower latency.</li>
            <li>🔹 Add batch processing support.</li>
            <li>🔹 Build a simple web UI for uploads.</li>
            <li>🔹 Fine-tune the model for domain-specific captions.</li>
        </ul>
    </div>

    <div class="section">
        <h2>🤝 Contributing</h2>
        <p>Contributions are welcome! Feel free to submit a pull request with improvements.</p>
    </div>

</div>

</body>
</html>
