### Hi there 👋

```php
function work_life_balance($task, $mood = 'neutral') {
    // Fun emojis based on mood
    $fun_emojis = array(
        'happy' => '😄',
        'neutral' => '😐',
        'sad' => '😞'
    );

    // Professional advice based on mood
    $professional_advice = array(
        'happy' => "Great! But don't forget your responsibilities.",
        'neutral' => "Stay balanced, don't overwork or overplay.",
        'sad' => "Maybe take a short break and come back stronger."
    );

    // Check if mood is valid
    if (!array_key_exists($mood, $fun_emojis)) {
        return "Invalid mood! Please choose between 'happy', 'neutral', or 'sad'.";
    }

    // Construct the message
    return "Task to complete: $task " . $fun_emojis[$mood] . ". "
           . "Advice: " . $professional_advice[$mood];
}

// Example usage
$message = work_life_balance("Complete PHP project", "happy");
echo $message;

```

<!--
**odgon/odgon** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

Here are some ideas to get you started:

- 🔭 I’m currently working on ...
- 🌱 I’m currently learning ...
- 👯 I’m looking to collaborate on ...
- 🤔 I’m looking for help with ...
- 💬 Ask me about ...
- 📫 How to reach me: ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...
-->
