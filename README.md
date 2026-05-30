# 🖼️ Image Generator

A sleek image search engine powered by Unsplash API. Find and explore millions of stunning images with an intuitive, modern interface.

## ✨ Features

- 🔍 **Instant Search** - Search for any image using keywords
- 🎨 **Beautiful Gallery** - Smooth grid layout with hover effects
- ⚡ **Fast Loading** - Optimized performance and quick results
- 📸 **Direct Links** - Click images to view on Unsplash
- 📌 **Pagination** - Load more results with one click
- 🌈 **Modern UI** - Gradient backgrounds and smooth animations

## 🚀 Quick Start

### Prerequisites
- Node.js (v14+)
- npm or yarn
- Unsplash API Key

### Installation

```bash
git clone https://github.com/rudra610prakash-code/Image-generator.git
cd Image-generator
npm install
npm start
```

Open `http://localhost:3000` in your browser and start searching!

## 🛠️ Tech Stack

- **HTML5** - Semantic markup
- **CSS3** - Gradients, animations, grid layout
- **JavaScript** - Async/await, DOM manipulation
- **Unsplash API** - High-quality image data source

## 🔑 Unsplash API Integration

This project uses the **Unsplash API** to fetch high-quality images.

### Getting Your API Key

 Create a new account or sign in
 Create a new application
 Copy your **Access Key**

### Configuration

Add your API key to `script.js`:



### API Endpoints Used

- **Search Photos** - `/search/photos`
  - Returns paginated search results
  - Supports filters like `page`, `query`, `per_page`
  - Currently fetches 12 images per request

```javascript
const url = `https://api.unsplash.com/search/photos?page=${page}&query=${keyword}&client_id=${accessKey}&per_page=12`;
```

### API Features

- ✅ **Free to Use** - 50 requests/hour for development
- ✅ **High-Quality Images** - Professional-grade photography
- ✅ **Pagination Support** - Load unlimited results
- ✅ **Direct Attribution** - Images link back to Unsplash
- ✅ **Fast Response** - Optimized CDN delivery
- ✅ **Rich Metadata** - Image details and photographer info

### Rate Limiting

- **Development**: 50 requests/hour
- **Production**: Contact Unsplash for higher limits
- Check remaining requests in response headers

## 📖 How It Works

1. Type a keyword in the search box
2. Click "Search" or press Enter
3. API fetches images matching your query
4. Browse beautiful images in grid layout
5. Click any image to view on Unsplash
6. Click "Show More" to load next page (page += 1)


## 🎯 Key Features

- **Grid Layout** - 3-column responsive grid
- **Smooth Animations** - Hover effects with scale & shadow
- **Pagination** - Fetch 12 images per page
- **Async/Await** - Modern fetch implementation
- **Modern Design** - Purple-to-blue gradient theme
  
---
## 📸 Screenshot
<img width="1291" height="538" alt="image" src="https://github.com/user-attachments/assets/a49b1589-0202-4a04-b68b-d91cb44eb55a" />


---

<img width="1306" height="561" alt="image" src="https://github.com/user-attachments/assets/b21748c6-921a-4a79-a912-629401816c4e" />


---

<img width="1299" height="571" alt="image" src="https://github.com/user-attachments/assets/1c23bbca-fc4d-4325-a866-9876ce4374aa" />





**Happy Searching!** 🚀
