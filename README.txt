python -m venv virtual
virtual/bin/pip freeze > requirements.txt
virtual/bin/pip install -r requirements.txt
virtual/bin/python -m streamlit run Demos/face_mesh_app.python