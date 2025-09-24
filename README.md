REQUIREMENTS

dependencies = [
    'tkinter', 'ttk', 'scrolledtext', 'messagebox', 'filedialog',
    'requests', 're', 'os', 'time', 'random', 'threading',
    'urllib.parse', 'json', 'webbrowser', 'queue', 'socket',
    'sys', 'zipfile', 'shutil'
]

print("Vérification des dépendances...")
for dep in dependencies:
    try:
        __import__(dep)
        print(f"✓ {dep} - OK")
    except ImportError:
        print(f"✗ {dep} - MANQUANT")

print("\nVérification terminée!")
