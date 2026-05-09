​Maarif-Copyright: Secure Design Previewer
​Project Overview
​Maarif-Copyright is a web-based security tool developed to protect the Intellectual Property (IP) of graphic designers during the client approval phase. It provides a secure environment for clients to review designs while implementing technical deterrents against unauthorized capturing, such as right-click saving and high-quality screenshots.
​The Problem
​In a fast-paced design environment like Dar Al Maarif, sending high-resolution proofs to clients before final payment poses a risk of asset theft via simple screenshots or browser "Save Image" functions.  
​Features & Security Logic
​Anti-Screenshot Blur: The design remains blurred by default using CSS filters to prevent static screen captures. It only reveals the clear image when the user actively holds down the left-click.
​Right-Click Disable: Integrated JavaScript prevents the standard context menu, stopping users from easily saving the image file.
​Dynamic Watermarking: A permanent "Property of Dar Al Maarif" overlay ensures that even if a hardware-level capture occurs, the asset remains unusable for production.
​Metadata Protection: Designed to be used in conjunction with metadata scrubbing to prevent information leakage.
​Impact
​Asset Protection: Provides a psychological and technical barrier against the unauthorized use of unpaid work.
​Professional Branding: Maintains a secure and professional interface for client interactions, bridging the gap between creative output and technical security.
​Usage
​Host the index.html file on a secure web server.
​Place your design file in the same directory.
​Send the unique preview link to the client for review.
