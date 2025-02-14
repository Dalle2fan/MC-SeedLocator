# **Advanced Minecraft Seed Finder Website**  

## **Website:** [mc-seed-finder.replit.app](https://mc-seed-finder.replit.app/)  

## **Overview**  
This tool automates finding Minecraft seeds based on specific biomes, structures, and terrain features. Supports Java and Bedrock editions (1.18 to 1.21.4)

## **Features**  
- Define custom biomes, including islands, valleys, and encircling terrain 
- Find structures with biome constraints, height ranges, and minimum counts  
- Locate clustered structures and biome combinations  
- Set biome size requirements for more precise world generation  

## **Usage**  
1. Define search parameters  
2. Select Minecraft version and edition  
3. Set search center using coordinates or spawn point  
4. Choose search radius (up to 10,000 blocks)  
5. Run the scan  

## **Installation**  

### **Clone the Repository**  
```bash
git clone https://github.com/Dalle2fan/MC-SeedLocator.git
cd MC-SeedLocator
```

### **If you don't have Homebrew installed yet**
```bash
/bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/HEAD/install.sh)"
```

### **Install Dependencies**  
```bash
npm install
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
