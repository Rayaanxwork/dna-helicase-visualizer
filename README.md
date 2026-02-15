# 🧬 DNA Helicase Visualizer

**An interactive web-based tool to visualize and analyze DNA sequences with stunning 3D animations**

[![Live Demo](https://img.shields.io/badge/demo-live-brightgreen)](https://rayaanxwork.github.io/dna-helicase-visualizer/)
[![License](https://img.shields.io/badge/license-MIT-blue.svg)](LICENSE)
[![HTML5](https://img.shields.io/badge/HTML5-E34F26?logo=html5&logoColor=white)]()
[![CSS3](https://img.shields.io/badge/CSS3-1572B6?logo=css3&logoColor=white)]()
[![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?logo=javascript&logoColor=black)]()

## ✨ Features

### 🎨 3D DNA Helix Visualization
- **Real-time rendered** double helix animation using HTML5 Canvas
- Interactive rotation controls with adjustable speed
- Smooth animations with depth perception
- Beautiful gradient effects and particle backgrounds

### 🔬 Sequence Analysis Tools
- **GC Content Calculator** - Calculate guanine-cytosine percentage
- **Molecular Weight Estimator** - Approximate DNA strand weight in Daltons
- **Nucleotide Distribution** - Visual bar chart showing A, T, G, C counts
- **Reverse Complement Generator** - Instant reverse complement calculation
- **mRNA Transcription** - Convert DNA to mRNA sequence

### 💻 User Interface
- Modern dark theme with purple gradients
- Responsive design that works on all devices
- Clean, intuitive interface
- Real-time preview of entered sequences
- Random sequence generator for testing

## 🚀 Live Demo

Try it out: **[https://rayaanxwork.github.io/dna-helicase-visualizer/](https://rayaanxwork.github.io/dna-helicase-visualizer/)**

## 📸 Screenshots

*Experience the beautiful interface with animated DNA visualization and comprehensive analysis tools*

## 🛠️ Technologies Used

- **HTML5** - Structure and Canvas API for rendering
- **CSS3** - Modern styling with gradients and animations
- **Vanilla JavaScript** - No frameworks, pure JS performance
- **Canvas API** - 3D-style helix rendering
- **Google Fonts** - Space Grotesk typography

## 💡 How to Use

1. **Enter a DNA Sequence**
   - Type or paste any DNA sequence (A, T, G, C)
   - Invalid characters are automatically filtered

2. **Click Visualize**
   - Watch the 3D helix animate
   - View instant analysis results

3. **Explore Analysis**
   - Check GC content percentage
   - View nucleotide distribution
   - Generate reverse complement
   - See mRNA transcription

4. **Control the Helix**
   - Toggle rotation on/off
   - Adjust animation speed

## 🧪 Example Sequences

Try these sample DNA sequences:

```
ATGCGATCGATCGTAGCTAGCTAG
GGCCTTAAGGCCTTAAGGCC
ATGGCCAATTGGCCAAGGTT
```

## 🎓 Educational Value

Perfect for:
- **Biology Students** - Understand DNA structure and complementarity
- **Bioinformatics Learners** - Practice sequence analysis
- **Teachers** - Interactive classroom demonstrations
- **Developers** - Learn Canvas API and biological data visualization

## 📦 Installation & Setup

### Option 1: Use Online
Just visit the [live demo](https://rayaanxwork.github.io/dna-helicase-visualizer/)

### Option 2: Run Locally

```bash
# Clone the repository
git clone https://github.com/Rayaanxwork/dna-helicase-visualizer.git

# Navigate to directory
cd dna-helicase-visualizer

# Open in browser
# Simply open index.html in your web browser
# No build process or dependencies required!
```

## 📁 Project Structure

```
dna-helicase-visualizer/
│
├── index.html          # Main HTML structure
├── styles.css          # All styling and animations
├── script.js           # DNA visualization and analysis logic
└── README.md          # This file
```

## 🧬 How It Works

### DNA Helix Rendering
The 3D helix effect is created using:
- Parametric equations for helix coordinates
- Sine/cosine functions for rotation
- Depth-based sizing and opacity
- RequestAnimationFrame for smooth 60fps animation

### Sequence Analysis
- **GC Content**: `(G + C) / Total × 100`
- **Molecular Weight**: Sum of nucleotide weights
  - Adenine (A): 313.21 Da
  - Thymine (T): 304.2 Da
  - Guanine (G): 329.21 Da
  - Cytosine (C): 289.18 Da

## 🎯 Future Enhancements

- [ ] ORF (Open Reading Frame) finder
- [ ] Protein translation
- [ ] Restriction enzyme site detection
- [ ] BLAST-like sequence alignment
- [ ] Export analysis results as PDF
- [ ] Multiple sequence comparison
- [ ] Melting temperature calculator

## 🤝 Contributing

Contributions are welcome! Feel free to:
- Report bugs
- Suggest new features
- Submit pull requests
- Improve documentation

## 👨‍💻 Author

**Built with 💜 by a student passionate about biology × technology**

Combining interests in molecular biology and web development to create educational tools that make science accessible and engaging.

## 📄 License

This project is open source and available under the [MIT License](LICENSE).

## 🌟 Acknowledgments

- Inspired by the beauty of molecular biology
- Built to help students visualize complex biological concepts
- Thanks to the open-source community

---

**⭐ Star this repo if you find it useful!**

**🔗 Connect:** [GitHub](https://github.com/Rayaanxwork) • [Live Demo](https://rayaanxwork.github.io/dna-helicase-visualizer/)
