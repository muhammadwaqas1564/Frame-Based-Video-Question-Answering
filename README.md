# Frame-Based-Video-Question-Answering
An AI-powered Frame-Based Video Question Answering (FB-VQA) system using the Qwen2-VL-2B-Instruct model to analyze key frames from videos and generate precise answers to user queries.


Overview:
The Frame-Based Video Question Answering (FB-VQA) System, developed by Team Zeta at ITSOLERA PVT LTD, is an advanced AI-driven solution designed to provide accurate answers to video-related questions. The system extracts key frames from videos and processes them using the Qwen2-VL-2B-Instruct model, a cutting-edge Vision-Language Model (VLM) capable of understanding complex video content and responding to user queries.

Features:
  Efficient Frame-Based Processing – Extracts and analyzes key frames instead of processing full-length videos.
  Natural Language Video Q&A – Users can ask questions like "What is happening in this video?" or "What is the color of the car?".
  Handles Long Videos – Supports videos longer than 20 minutes with high accuracy.
  User-Friendly Web App – Deployed with Streamlit for seamless user interaction.

Technologies Used:
  Deep Learning & Vision-Language Models (Qwen2-VL-2B-Instruct)
  PyTorch & Transformers (for model implementation)
  OpenCV & FFmpeg (for video frame extraction)
  Streamlit (for web-based user interface)
  Hugging Face APIs (for model integration)

Workflow:
  1. Video Upload – Users upload an MP4 video via the Streamlit web interface.
  2. Question Input – Users enter a natural language question about the video.
  3. Frame Extraction & Processing –
    Extracts 1 frame per second (FPS) for analysis.
    Resizes frames to 64x64, 128x128, or 512x512 pixels for efficiency.
    Tokenizes and processes the query.
      1. Answer Generation – The system analyzes frames and returns an accurate textual response.
    
    
