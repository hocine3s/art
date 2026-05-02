# **App Name**: Oran Canvas

## Core Features:

- Public Navigation & Hero: A vibrant hero section featuring the club's branding and tagline, complemented by a responsive navigation bar linking to core sections like Gallery, Events, Join Us, and Admin Login.
- Dynamic Art Gallery Display: Showcase student artwork in an engaging masonry or grid layout, with each piece displaying its image, artist's full name, a brief description, and a clickable link to the artist's profile. Artwork data will be stored using Firebase's database services.
- Events Showcase: Highlight upcoming and past club activities, workshops, and exhibitions, each with a cover image, title, date, time, and location. Event data will be managed and displayed from Firebase's database services.
- Membership Registration: A user-friendly form allowing students to register for the club by providing their full name, email, phone number, university department/major, and an optional portfolio link. Submissions are securely saved to Firebase's database services.
- Secure Admin Access: Implement a protected administrative route ('/admin') secured by a Firebase Authentication system, ensuring only authorized club administrators can access sensitive management features.
- Artwork & Event Content Management: An administrative interface for club staff to perform CRUD operations (Create, Read, Update, Delete) on gallery artworks (including image uploads to Firebase Storage) and event listings stored in Firebase's database services. This includes an AI tool to assist in generating creative descriptions for new artworks based on provided details.
- Registered Members Viewer: A secure admin dashboard section providing a structured table view of all registered club members, enabling administrators to easily browse member details fetched from Firebase's database services.

## Style Guidelines:

- Primary color: An energetic magenta (#E540A9) to convey artistic passion, youthfulness, and creativity. This vibrant hue will be used for interactive elements, calls-to-action, and key headings to capture attention.
- Background color: A soft, barely-there pinkish-white (#F7F0F5), providing a clean, elegant, and understated canvas. Its subtle warmth will create a harmonious balance that allows the primary color and diverse artworks to stand out without distraction.
- Accent color: A deep, rich violet (#9312C2) for powerful emphasis and visual contrast. This color will be sparingly used for important highlights, unique features, or as a strong visual differentiator within the layout.
- Headline font: 'Playfair' (serif) for an elegant, high-fashion, and artistic statement, perfectly suited for titles and short, impactful statements. Body font: 'PT Sans' (sans-serif) for its modern readability, subtle warmth, and versatility in displaying longer blocks of text across the website.
- Employ a consistent set of modern, minimalist line-art icons that subtly reflect artistic tools, creativity, community, and events. Icons should have a light aesthetic, complementing the overall youthful and artistic tone of the website.
- A fully responsive and adaptive layout will be implemented, featuring a dynamic masonry or grid design for the art gallery. Information will be presented with clear hierarchy and generous white space to enhance readability and visual appeal across all device types.
- Subtle and smooth hover effects will be integrated throughout the site on interactive elements such as artwork cards, navigation links, and buttons. These gentle animations will provide engaging visual feedback without distracting from the artistic content.