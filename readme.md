
# Chatgpt-Arcana

## About

Chatgpt-Arcana is an Emacs Lisp package that gives you arcane powers. Yer a space wizard now, Harry.

## Examples

https://user-images.githubusercontent.com/859820/222489571-27901725-158e-4a2a-899a-36a3f4eea2c1.mp4

https://user-images.githubusercontent.com/859820/222561453-031d271f-4fee-46f4-b63e-734729e01745.mp4

https://user-images.githubusercontent.com/859820/222563046-5928a98d-7498-4bce-9916-f5a7d24acc81.mp4

## Installation

Chatgpt-Arcana isn’t on melpa or elpa. You can use use-package to install from github:

```elisp
(use-package chatgpt-arcana
  :straight (:host github :repo "CarlQLange/Chatgpt-Arcana.el" :files ("*.el"))
  :init (setq chatgpt-arcana-api-key "your-api-key-here"))
```

I have to stress at this point that this package is very new, and I only wrote it to scratch an itch. Sorry if it turns you into a chicken or something.

## Usage

There are various interactive functions available, such as `chatgpt-arcana-replace-region`, `chatgpt-arcana-insert-at-point`, and more. Certain ones even work.

## Requirements

You will need to have an API key from OpenAI’s GPT-3 language model to use this package, and set it as `chatgpt-arcana-api-key`. You can sign up for an API key on the OpenAI website. Depending on how much you use the package, the API cost may vary.

I strongly recommend setting a low usage limit on your account to stop runaway spending. The default model is quite cheap but it costs nothing to be prudent.

## Credits

This package was developed by Carl Lange with judicious help from ChatGPT. 

## License

This package is licensed under the [GNU General Public License v3.0](https://www.gnu.org/licenses/gpl-3.0.en.html).
*Important note*: code generated by ChatGPT probably has a massive license headache attached to it and may result in RMS eating your dog.
