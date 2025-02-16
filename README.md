# **Advanced Minecraft Seed Finder Website**  

## **Website:** [mc-seed-finder.replit.app](https://mc-seed-finder.replit.app/)  

### *(If website is down, you can use the seed finder by following the Installation)*

## **Overview**  
This tool automates finding Minecraft seeds based on specific biomes, structures, and terrain features. Supports Java and Bedrock editions (1.18 to 1.21.4)

## **Features**  
- Find any biomes including custom biomes (like islands, valleys, and elevated encircling terrain)
- Find structures with biome constraints, height ranges, and minimum counts  
- Locate clustered structures (structures next to each other) and biome combinations  
- Set biome size requirements for more precise world generation  

## **Usage**  
1. Define search parameters  
2. Select Minecraft version and edition  
3. Set search center using coordinates or spawn point
4. Set the seed requirments (such as at least 1 village and Cherry Grove within 500 block search radius from spawn for example)
6. Run the scan, might taKe a few minutes depending on the rarity of the seed requirements

## **Installation**  

### **Clone the Repository**  
```bash
git clone https://github.com/Dalle2fan/MC-SeedLocator.git
cd MC-SeedLocator
```

### **If you don't have NodeJS installed yet, use Homebrew to install it**
```bash
/bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/HEAD/install.sh)"
brew install node
```

### **Install Dependencies**  
```bash
npm install express p-limit --save
```

### **Run the Application**  
```bash
npm start
```
Visit `http://localhost:3000` in a browser.  

## **Docker**  
To build and run using Docker:  
```bash
docker build -t mc-seed-finder .
docker run -p 3000:3000 --env-file .env mc-seed-finder
```

## **Deployment**  
This project can be deployed using:  
- **Vercel** (Frontend)  
- **Railway / Render** (Backend)  
- **GitHub Pages** (Static Frontend)  
- **Heroku / Fly.io** (Full-stack Hosting)  

## **Contributing**  
1. Fork the repository  
2. Create a new branch (`git checkout -b feature-branch`)  
3. Commit changes (`git commit -m "Added feature"`)  
4. Push and submit a pull request  

## **License**  
This project is licensed under the MIT License.
