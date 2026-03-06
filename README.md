# ChildSafeAI

ChildSafeAI is a quick project we built as a **team during the ChildSafeAI Hackathon at 42 Heilbronn**.

It's a reverse proxy that scans the connection between a kid's device and the web, trying to remove content that's not suitable — both text and images. The goal? Helping keep kids safe online.  

## How to run it ?

To run the project, you can execute the following command, but make sure that you have mitmproxy ready:

```bash
mitmweb -s filter.py --quiet
