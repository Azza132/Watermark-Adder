MARK — Video Watermark Tool
Created by Aaron Sermon

---

OVERVIEW

MARK is a browser-based video watermark tool that lets you add text or image watermarks to any video file, entirely on your own device. No uploads, no accounts, no internet connection required after the page loads. Just open the HTML file in a modern browser and you're good to go.

---

HOW TO USE

1. Open watermark-adder.html in your browser (Chrome or Edge recommended for best export support).

2. Load your video by either dragging and dropping a video file onto the upload area, or clicking it to browse your files. MP4, MOV, WEBM, and AVI are all supported.

3. Choose your watermark type using the Text or Image toggle in the right-hand panel.

   If you choose Text:
   - Type your watermark text into the text field (e.g. "© My Brand")
   - Choose a font from the dropdown
   - Set the font size in pixels
   - Pick a colour using the colour picker

   If you choose Image:
   - Click the file input to upload a PNG or image file (PNG with transparency works best)
   - Use the Size slider to control how large the watermark appears relative to the video width

4. Set the position of your watermark using the 3x3 position grid. Click any of the nine squares to place the watermark in that region of the video — corners, edges, or centre.

5. Adjust Opacity to make the watermark more or less transparent, and Padding to control how far it sits from the edges.

6. Use the scrubber bar beneath the preview to drag through your video and check how the watermark looks on different frames.

7. When you're happy, click Export Watermarked Video. The tool will process the video frame by frame and show you a progress percentage as it works.

8. Once processing is complete, a Download button will appear. Click it to save your watermarked video. The file will be saved as a WEBM or MP4 depending on your browser's support.

---

TECHNICAL NOTES

- All processing happens locally in your browser using the Canvas API and the MediaRecorder API. Nothing is sent to any server.
- Export quality is set to 8 Mbps video bitrate, which is suitable for most use cases.
- Export speed depends on the length and resolution of your video and your device's performance. Longer or higher resolution videos will take more time.
- Chrome and Edge offer the best export compatibility. Firefox may export in WEBM only.
- For image watermarks, PNG files with a transparent background will give the cleanest result.
- The preview updates live as you adjust any setting, so you can fine-tune before exporting.

---

REQUIREMENTS

- A modern web browser (Chrome 88+, Edge 88+, or Firefox 90+ recommended)
- No installation, no dependencies, no internet connection needed

