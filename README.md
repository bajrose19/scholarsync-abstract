# scholarsync-abstract
Purpose:

The app is designed for science communication. It takes academic text (like a paper abstract) and converts it into a short, structured script suitable for viral science videos, following the HESS 5-Point Formula: Hook → Context → Science → So What → Call to Action (CTA). Users can choose to generate the script in English or Spanish.

What it does:

Input:

Users paste academic or scientific text.

Users select the output language (English or Spanish).

Processing:

Sends the input to a language model API with instructions to generate a concise script.

Uses exponential backoff for API calls to handle rate limits or retries.

Output:

Displays the generated script in five structured sections.

Shows a timetable for the suggested video flow (seconds for each section).

Allows users to copy the script to clipboard for use in content creation.

Key Features:

Only English and Spanish outputs are available.

Tailored for science outreach and education.

Clean, modern interface with Tailwind CSS styling.

Interactive buttons with loading spinner, error messages, and copy functionality.
