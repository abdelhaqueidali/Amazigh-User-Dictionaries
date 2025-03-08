# Amazigh User Dictionaries (Amazigh-User-Dictionaries)

This part of the repository contains user dictionaries designed for text prediction (autocompletion and suggestions) on software keyboards, specifically for the Amazigh language. These dictionaries are derived from reputable sources, providing a strong foundation for accurate and comprehensive word suggestions.

## Sources

The dictionaries are built from the following sources:

*   **DGLAi Dictionary:** "Dictionnaire Général de la Langue Amazighe" (General Dictionary of the Amazigh Language), a comprehensive Amazigh dictionary.  Having the dictionary data available is a significant resource.
*   **Amsfti:**  A resource specifically for Amazigh verbs. This is important because verbs have different conjugations that are not availabe in the DGLAi dictionary, so a dedicated verb dictionary is crucial for accurate prediction.

## File Format: `Amazigh.txt`

The primary dictionary file, `Amazigh.txt`, is a simple, plain text file with the following structure:

*   **One word per line:** Each line contains a single Amazigh word. This format is widely compatible with various keyboard software and dictionary import tools. This simplicity makes the dictionaries very easy to use and adapt.

## Importing the Dictionaries (UDM App)

The recommended method for importing these dictionaries into your keyboard software is to use a "User Dictionary Manager" (UDM) application.  It is capable of importing plain text word lists and associating them with specific language codes. You will find it on Play store. Or earch for terms like "user dictionary manager," "custom keyboard dictionary," or similar.

## Language Codes (Critical for Proper Functioning)

The correct language code is *absolutely essential* for the keyboard to use the dictionary correctly.  The Amazigh language (and its various dialects) uses several different language codes, depending on the keyboard and the specific variety of Amazigh.  The README provides a very helpful list of common codes:

*   **General Amazigh (Latin Script):**
    *   `ber`:  A common code for Berber (Amazigh) languages, often used for the Latin script variant.  This is a frequent choice for Samsung Keyboard.
    *   `ber-Latn`:  Explicitly specifies Berber using the Latin script. Used by Gboard (Google Keyboard).
    *   `kab`:  Used specifically for the Kabyle dialect of Amazigh.
*   **Amazigh (Tifinagh Script):**
     *    `ber-Tfng`
     *    `ber`
     *    `tf` : Used on Multiling O Keyboard
    *   `zgh`:  Another code used for Standard Moroccan Amazigh (SMA).
    *   `zgh-Tfng`

**Crucial Step: Identify Your Keyboard's Language Code:**  Before importing the dictionary, you *must* determine which language code your keyboard uses for Amazigh.  Check your keyboard's settings, language options, or documentation. Using the wrong code will prevent the dictionary from working correctly. The suggestions provided are a great starting point, but double-checking is vital.

## `Amazigh.txt` vs. `Amazigh (Latin).txt`

*   **`Amazigh.txt`:**  This is a Tifinagh version

*   **`Amazigh (Latin).txt`:** This the Latin version transliterated from the original Tifinagh version

## Summary of Usage Steps

1.  **Identify Your Keyboard:** Determine which keyboard app you are using (e.g., Gboard, Samsung Keyboard, Multiling O Keyboard).

2.  **Find the Amazigh Language Code:** Look in your keyboard's settings to find the exact language code it uses for Amazigh (e.g., `ber`, `ber-Latn`, `kab`, etc.).

3.  **Download `Amazigh.txt`:** Obtain the `Amazigh.txt` file from this repository.

4.  **Import with UDM App:** Use a User Dictionary Manager app to import the `Amazigh.txt` file.  *Crucially*, associate the imported dictionary with the correct Amazigh language code you identified in step 2.

5.  **Test:**  Start typing in Amazigh using your keyboard.  You should see word suggestions appear based on the imported dictionary.

## Key Benefits of Using These Dictionaries

*   **Improved Typing Accuracy:**  Reduces typos and helps you write in Amazigh more quickly and efficiently.
*   **Faster Text Input:**  Word suggestions speed up the typing process significantly.
*   **Comprehensive Vocabulary:**  The dictionaries are based on authoritative sources (IRCAM, DGLAi, Amsfti), providing a broad range of Amazigh words.
*   **Easy to Use:**  The plain text format and clear instructions make the dictionaries accessible to a wide range of users.
