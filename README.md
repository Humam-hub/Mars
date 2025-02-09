# Mars Explorer 🚀

An interactive web application built with Streamlit that provides comprehensive information about Mars, featuring real-time NASA data, AI-powered chat, and educational quizzes.

## Features

### 🏠 Home Dashboard
- Dynamic welcome interface with latest Mars updates
- NASA's Astronomy Picture of the Day (APOD) integration
- Recent mission highlights and discoveries

### 🤖 AI Chatbot
- Interactive conversations about Mars and space exploration
- Powered by Groq's LLM API
- Contextual responses with scientific accuracy

### 📊 Mars Information Center
- Comprehensive Mars facts and statistics
- Interactive slideshow of Mars features:
  - Olympus Mons
  - Valles Marineris
  - Polar Ice Caps
  - Impact Craters
- Research updates and mission timelines

### 🛸 NASA Data Integration
- Real-time Mars weather data visualization
- Mars Rover photo gallery with filtering options
- Mission status updates and statistics

### 🎮 Space Quiz
- Progressive difficulty levels
- AI-generated questions about Mars and space
- Immediate feedback and explanations
- Progress tracking system

## Installation
```
# Clone the repository:
git clone https://github.com/Humam-hub/Mars.git 

# Install required packages:
pip install -r requirements.txt

# Set up environment variables:
Create a `.env` file with:

GROQ_API_KEY=your_groq_api_key
NASA_API_KEY=your_nasa_api_key

# Run the application:
streamlit run app.py
```
## Project Structure
```
mars-explorer/
├── app.py # Main application file
├── requirements.txt # Project dependencies
├── sections/
│ ├── 1_AIChatbot.py # AI chat implementation
│ ├── 2_MarsInformation.py # Mars facts and features
│ ├── 3_NASAData.py # NASA API integration
│ └── game.py # Quiz implementation
└── utils.py # Utility functions
```
## Dependencies

- Streamlit
- Groq
- Plotly
- Pandas
- Requests
- python-dotenv

## API Integration

The project integrates with two main APIs:
1. NASA API - For APOD and Mars data
2. Groq API - For AI chat functionality

## Contributing

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## License

This project is licensed under the MIT License - see the LICENSE file for details.

## Acknowledgments

- NASA Open APIs
- Groq AI
- Streamlit Community
- Mars Science Laboratory Mission

## 👥 Our Stellar Team

<div align="center">
<table>
<tr>
    <td align="center">
        <img src="https://avatars.githubusercontent.com/u/73097560?v=4" width="100px;" style="border-radius: 50%;" alt="Muhammad Humam"/><br>
        <b>Muhammad Ibrahim Qasmi</b><br>
        <sub>Project Lead</sub><br>
        <a href="https://github.com/Humam-hub"><img src="https://cdn-icons-png.flaticon.com/24/25/25231.png" width="16px"></a>
        <a href="https://linkedin.com/in/muhammad-humam-tahir-470267178/"><img src="https://cdn-icons-png.flaticon.com/24/61/61109.png" width="16px"></a>
    </td>
    <td align="center">
        <img src="https://avatars.githubusercontent.com/u/73097560?v=4" width="100px;" style="border-radius: 50%;" alt="Sarah Chen"/><br>
        <b>Tayyab Sajjad</b><br>
        <sub>AI Engineer</sub><br>
        <a href="https://github.com/sarahchen"><img src="https://cdn-icons-png.flaticon.com/24/25/25231.png" width="16px"></a>
        <a href="https://linkedin.com/in/sarahchen"><img src="https://cdn-icons-png.flaticon.com/24/61/61109.png" width="16px"></a>
    </td>
    <td align="center">
        <img src="https://avatars.githubusercontent.com/u/73097560?v=4" width="100px;" style="border-radius: 50%;" alt="David Rodriguez"/><br>
        <b>Zeeshan Younus</b><br>
        <sub>Frontend Expert</sub><br>
        <a href="https://github.com/davidr"><img src="https://cdn-icons-png.flaticon.com/24/25/25231.png" width="16px"></a>
        <a href="https://linkedin.com/in/davidr"><img src="https://cdn-icons-png.flaticon.com/24/61/61109.png" width="16px"></a>
    </td>
</tr>
<tr>
    <td align="center">
        <img src="https://avatars.githubusercontent.com/u/73097560?v=4" width="100px;" style="border-radius: 50%;" alt="Emma Patel"/><br>
        <b>Ubaid Ullah</b><br>
        <sub>Backend Developer</sub><br>
        <a href="https://github.com/emmapatel"><img src="https://cdn-icons-png.flaticon.com/24/25/25231.png" width="16px"></a>
        <a href="https://linkedin.com/in/emmapatel"><img src="https://cdn-icons-png.flaticon.com/24/61/61109.png" width="16px"></a>
    </td>
    <td align="center">
        <img src="https://avatars.githubusercontent.com/u/73097560?v=4" width="100px;" style="border-radius: 50%;" alt="Liam Johnson"/><br>
        <b>Tayyab Hussain</b><br>
        <sub>Data Scientist</sub><br>
        <a href="https://github.com/liamj"><img src="https://cdn-icons-png.flaticon.com/24/25/25231.png" width="16px"></a>
        <a href="https://linkedin.com/in/liamj"><img src="https://cdn-icons-png.flaticon.com/24/61/61109.png" width="16px"></a>
    </td>
    <td align="center">
        <img src="https://avatars.githubusercontent.com/u/73097560?v=4" width="100px;" style="border-radius: 50%;" alt="Sophia Lee"/><br>
        <b>Humam Tahir</b><br>
        <sub>DevOps Engineer</sub><br>
        <a href="https://github.com/sophial"><img src="https://cdn-icons-png.flaticon.com/24/25/25231.png" width="16px"></a>
        <a href="https://linkedin.com/in/sophial"><img src="https://cdn-icons-png.flaticon.com/24/61/61109.png" width="16px"></a>
    </td>
</tr>
</table>
</div>
