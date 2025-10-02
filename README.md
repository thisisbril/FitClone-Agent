# FitClone 🎨👗

**AI-Powered Fashion Color Variant Generator**

FitClone is an intelligent AI agent built on Google Gemini that generates photorealistic color variants of fashion photographs while preserving every other aspect of the original image - from model pose to lighting to background.

## 🌟 Overview

FitClone solves a critical challenge in fashion e-commerce: showcasing multiple color variants without the expense of multiple photoshoots. By using advanced AI image generation, FitClone creates new product photos that look professionally shot in different colors.

## ✨ Key Features

- **🎯 Precision Color Transfer**: Applies new colors from reference images while maintaining photographic realism
- **🔒 Complete Preservation**: Keeps model pose, lighting, shadows, highlights, and background identical
- **📐 Professional Quality**: Generates high-resolution, photorealistic fashion images
- **⚡ Cost-Effective**: Eliminates the need for multiple expensive photoshoots
- **🎨 Flexible Input**: Accepts various color references (fabric swatches, color samples, other garments)

## 🚀 What FitClone Does

Given:
1. An original fashion photograph
2. A color reference image

FitClone generates:
- A new photograph with the garment in the reference colors
- Identical composition, lighting, and model pose
- Natural color integration with realistic shadows and highlights
- Professional photography quality output

## 🛠️ Technology Stack

- **AI Model**: Google Gemini 2.5 Flash (with image generation capabilities)
- **Prompt Engineering**: POML (Prompt Orchestration Markup Language)
- **Platform**: Google Gemini Gem (AI Agent)

## 📋 Use Cases

- **E-commerce Fashion Stores**: Display multiple color variants without additional photoshoots
- **Fashion Designers**: Visualize designs in different colorways before production
- **Fashion Marketplaces**: Provide consistent product imagery across color options
- **Fashion Startups**: Reduce initial photography costs while maintaining professional presentation
- **Wholesale Fashion**: Show buyers multiple color options without physical samples

## 🎯 How It Works

1. **Upload** your original fashion photograph
2. **Provide** a color reference image (fabric swatch, color sample, or reference garment)
3. **Specify** which garment element should receive the color change
4. **Receive** a photorealistic image with the color variant applied

## 📝 System Prompt Architecture

FitClone uses a structured POML-based system prompt that includes:

- Clear role definition and task specification
- Step-by-step processing instructions
- Critical preservation requirements
- Color application guidelines
- Quality control standards
- Usage examples for consistent behavior

## 🔧 Setup & Deployment

### Prerequisites
- Gemini Gem creation permissions
- POML extension for VSCode (for development)

### Installation

1. Clone this repository:

2. Review the system prompt file

3. Create a new Gem on Google Gemini platform

4. Copy the POML system prompt into your Gem configuration

5. Test with sample fashion images

## 📖 Usage Guidelines

### Input Requirements

**Original Photo:**
- Clear, well-lit fashion photograph
- Garment clearly visible
- Professional or semi-professional quality recommended

**Color Reference:**
- Image containing desired color palette
- Can be fabric swatches, color samples, or other garments
- Clear, accurate color representation

### Best Practices

- Use high-resolution images for best results
- Ensure good lighting in original photos
- Provide clear color references
- Specify exactly which garment element to recolor
- Test with multiple reference angles if needed

## 🎨 Example Workflow

```
User: "I have a photo of a model wearing a blue dress in a studio. 
Here's a red color reference. Generate the dress in red."

FitClone: [Analyzes composition, extracts red color, applies to dress 
while preserving model pose, studio lighting, and background]

Output: Professional photograph with red dress, identical in every 
other aspect to the original
```

## 🔐 Privacy & Security

- No images are stored permanently by FitClone
- Process images according to Google Gemini's privacy policies
- Ensure you have rights to all uploaded images

## 🤝 Contributing

Contributions, issues, and feature requests are welcome!

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request



## 🙏 Acknowledgments

- Google Gemini team for the powerful AI capabilities
- Microsoft POML for structured prompt engineering
