const terry = {
  name: "Terrance Ruppel",
  location: "New Orleans",
  role: "Software Developer",
  currentlyLearning: [
    "React",
    "Python",
    "REST APIs",
    "Git"
  ],
  currentlyBuilding: [
    "Band Analytics Dashboard",
    "WordPress Projects"
  ],
  hobbies: ["🥁 Drumming", "🎵 Live Music", "📷 Photography"]
};

export default function Profile() {
  return (
    <>
      <h1>Hi, I'm {terry.name}</h1>
      <p>Building cool things one commit at a time.</p>
    </>
  );
}
