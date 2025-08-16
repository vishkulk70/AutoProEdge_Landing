[page.js](https://github.com/user-attachments/files/21811681/page.js)
import Landing from "../components/Landing";

export default function Page() {
  return <Landing />;
}
[layout.js](https://github.com/user-attachments/files/21811683/layout.js)
export const metadata = {
  title: "AutoPro EDGE – Accelerate Your Automotive Marketing Career",
  description: "Coaching platform for mid-career automotive marketing professionals in India.",
  openGraph: {
    title: "AutoPro EDGE",
    description: "Your ignition key to transformation in Automotive Marketing.",
    url: "https://autoproedge.com",
    siteName: "AutoPro EDGE",
    images: [
      {
        url: "/og-image.png",
        width: 1200,
        height: 630,
      },
    ],
    locale: "en_IN",
    type: "website",
  },
};

export default function RootLayout({ children }) {
  return (
    <html lang="en">
      <body>{children}</body>
    </html>
  );
}
