- š Hi, Iām @Akramskii
- š Iām interested in ...
- š± Iām currently learning ...
- šļø Iām looking to collaborate on ...
- š« How to reach me ...

<!---
Akramskii/Akramskii is a āØ special āØ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->


$nomention
$addCmdReactions[$getVar[correct]]
$onlyForServers[738747595438030888;]
$addReactions[ā¬;ā¬;š¶]
$onlyIf[$checkContains[$message[1];Server;CRBT;Other;clembs.xyz]==true;$getVar[wrong] **You need to suggest something with that theme:** Server, CRBT, Other or clembs.xyz]

$useChannel[channel ID]

$authorIcon[$authorAvatar]
$author[$username#$discriminator[$authorID]]

$title[Suggestion // $message[1]]

$description[```$replaceText[$message;$message[1];;1]```]

$footer[ā¬ļø Upvote - ā¬ļø Downvote - ā Will be added - ā Won't be added - š¶ Already added]

$color[$getVar[border color]]
