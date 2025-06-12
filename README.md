# 2D-to-3D Asset-Generator

2D to 3D Asset Generator project is develop to convert 2D images into 3D images.

#FLOWCHART/PROCESS
1. User upload an 2D image.
2. (Image preprocessing (If needed))
   -Resize, normalize, remove background (optional)
3. (tripoSR Model Inference)
   -Load model
   -Feed preprocessed 2D image
   -Generate 3D mesh (ex., .obj or .glb)
4. (Postprocessing)
   -Mesh cleanup
   -Texture mapping
   -Format conversion if needed
5. (Visualization & Preview)
   -Render 3D model in viewer (ex.,using three.js or stpyvista in streamlit)
6. (Downoad option/Export)
   -Download .obj/.glb
   -Optionally upload to cloud or export to unity/unreal            
