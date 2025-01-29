# Mad Libs Generator

This Python program is a simple Mad Libs generator. It reads a story template from a text file, extracts placeholder words, and prompts the user to provide replacements for those placeholders. Once the user has entered their words, the story is updated and printed with the user-provided inputs.

## How It Works

1. The program reads the story template from a file named story.txt.

2. It looks for placeholders in the format <word> within the story.

3. All unique placeholders are collected.

4. The program prompts the user to provide a replacement for each placeholder.

5. The placeholders in the story are replaced with the user-provided words.

6. The final story is printed with the user inputs.

### Example story.txt

You can create a file named story.txt with the following content:

One sunny day, I decided to go to the <place> with my <adjective> <animal>. We had so much fun! First, we played <verb> with a <color> <noun>. Then, we ate a <adjective> <food> and <verb> under the <adjective> tree.

### Usage

1. Make sure you have Python installed on your system.

2. Create a file named story.txt in the same directory as the script and add your story with placeholders in the format <word>.

3. Run the script using the command:

python madlibs.py

4. The program will prompt you to enter a word for each placeholder found in the story.

5. Once you've provided all the words, the completed story will be printed to the screen.

### Example Output

. Given the example story.txt above, the program might run as follows:

Enter a word for <place>: park
Enter a word for <adjective>: happy
Enter a word for <animal>: dog
Enter a word for <verb>: jump
Enter a word for <color>: red
Enter a word for <noun>: ball
Enter a word for <food>: sandwich

One sunny day, I decided to go to the park with my happy dog. We had so much fun! First, we played jump with a red ball. Then, we ate a happy sandwich and jumped under the happy tree.

### Notes

. Ensure the story.txt file exists and contains placeholders in the format <word>.

. Placeholders must be unique for accurate prompting and replacement.

. The script replaces all instances of a placeholder with the corresponding user-provided word.

