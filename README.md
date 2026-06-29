GroupDNA is a Python-based WhatsApp group chat analyser that parses raw .txt chat exports and generates a full personality and activity report for your group — no fancy libraries, just pure Python fundamentals + NumPy.

**Features:**
#FeatureDescription
1. Chat Parser : Converts raw WhatsApp .txt export into structured records, handles multiline messages, media, and deleted messages.
2. Group Overview : Message count per participant with a text-based bar chart.
3. Most Active Day & Hour : Finds the busiest day and peak chatting hour across the grou.
4. Activity Heatmap : Per-person heatmap showing chat intensity across all 24 hours.5
5. Top Words : Reveals the group's most-used words (with stopword filtering).6
6. Response Speed : Average response time and longest silent streak.
7. Personality Archetypes : Labels each member as one of: Spammer, Ghost, Night Owl, Early Bird, Storyteller, or Caretaker.

**Tech Stack**
Python — core fundamentals only (loops, dicts, functions, file I/O)
NumPy — for bar scaling and numerical operations
datetime — for timestamp parsing and time calculations
❌ No pandas  |  ❌ No matplotlib  |  ❌ No regex  |  ❌ No collections.Counter

**Note:**
Currently supports WhatsApp chat exports in DD/MM/YY, HH:MM timestamp format.
Designed for group chats (not DMs).
Uses a synthetic dataset (hostel_bois.txt) for demonstration.
