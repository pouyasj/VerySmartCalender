\# SmartCalendar (iOS)

SmartCalendar is an iOS calendar application built using \*\*SwiftUI\*\*, featuring:  
\- Year & month navigation  
\- Custom event creation  
\- Natural-language "Smart Input" parsing  
\- Minimal, dark, and modern UI design inspired by native Apple apps

\---

\#\# 📱 Features

\- View full year and select any month  
\- Tap a day to view all events assigned to that date  
\- Add events using:  
  \- \*\*Manual input\*\* (Title, Location, Start/End time)  
  \- \*\*Smart Input AI-style text parsing\*\*, e.g.:

    \`\`\`  
    Lunch with Sara at 2pm until 3pm in Via Toledo  
    \`\`\`

\- Automatic extraction of:  
  \- Title  
  \- Start time  
  \- End time  
  \- Location  
\- Visual event indicators (dots below calendar days)  
\- Clean card-style event list UI

\---

\#\# 🧠 Smart Input Parsing

The parser uses regular expressions to detect:  
\- Time ranges    
\- Single start time    
\- Location keywords (\`at\`, \`in\`, \`@\`)

Examples that work:

| Input Text | Parsed Output |  
|------------|----------------|  
| \`Meeting with John at 9\` | Title: \`Meeting with John\`, Time: \`09:00\` |  
| \`Dinner with Ali at 7pm until 10pm in Milano\` | \+ End time \+ Location |  
| \`Gym 18-19\` | 24h format supported |

\---

\#\# 🏗 Project Structure

