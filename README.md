- 👋 Hi, I’m @Akramskii
- 👀 I’m interested in ...
- 🌱 I’m currently learning ...
- 💞️ I’m looking to collaborate on ...
- 📫 How to reach me ...

<!---
Akramskii/Akramskii is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->


$nomention
$addCmdReactions[$getVar[correct]]
$onlyForServers[738747595438030888;]
$addReactions[⬆;⬇;🔶]
$onlyIf[$checkContains[$message[1];Server;CRBT;Other;clembs.xyz]==true;$getVar[wrong] **You need to suggest something with that theme:** Server, CRBT, Other or clembs.xyz]

$useChannel[channel ID]

$authorIcon[$authorAvatar]
$author[$username#$discriminator[$authorID]]

$title[Suggestion // $message[1]]

$description[```$replaceText[$message;$message[1];;1]```]

$footer[⬆️ Upvote - ⬇️ Downvote - ✔ Will be added - ❌ Won't be added - 🔶 Already added]

$color[$getVar[border color]]
