# Security Engineering - A Practical Approach

## 🚀 Getting Started

### Prerequisites
- Node.js (v14 or higher)
- npm or yarn

### Local Development

1. **Clone the repository**
   ```bash
   git clone <repository-url>
   cd mintlify-docs
   ```

2. **Install Mintlify CLI**
   ```bash
   npm install -g mintlify
   ```

3. **Start the development server**
   ```bash
   mintlify dev
   ```

4. **View the docs**
   Open `http://localhost:3000` in your browser


## 🛠️ Adding New Content

To add new sections to the book:

1. **Create MDX files** in the appropriate chapter directory
2. **Update `docs.json`** navigation to include new pages
3. **Follow naming convention**: `section_X_Y_descriptive_name.mdx`

### MDX File Template
```mdx
---
title: "Your Section Title"
description: "Brief description of the section content"
---

# Your Section Title

Your content here...
```

## 🎨 Configuration

Key files for customization:

- `docs.json` - Navigation and site configuration
- `index.mdx` - Homepage content
- `logo/` - Brand assets
- `images/` - Book images and diagrams

## 📝 Contributing

1. Fork the repository
2. Create a feature branch for new content
3. Add sections following the established structure
4. Update navigation in `docs.json`
5. Test locally with `mintlify dev`
6. Submit a pull request

## 🔗 Resources

- [Mintlify Documentation](https://mintlify.com/docs)
- [MDX Documentation](https://mdxjs.com/)
- [Security Engineering Resources](https://www.cl.cam.ac.uk/~rja14/book.html)

## 📄 License

This book is provided for educational and reference purposes.
