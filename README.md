# AVIP 2026 — Task 2: Image Generation with Pretrained Models

## Project overview
This repository contains 30 AI-generated images made using Google Flow with Nano Banana 2.1, as reported by the project author. The collection covers landscapes, architecture, wildlife, science fiction, product photography, and lifestyle scenes.

## Model and workflow
- **Tool:** Google Flow web interface
- **Model reported by author:** Nano Banana 2.1
- **Direct API usage:** None reported; images were generated through Flow.
- **Official image-generation documentation:** https://ai.google.dev/gemini-api/docs/image-generation
- **Official model card:** https://deepmind.google/models/model-cards/nano-banana-2-1/
- **Google Terms of Service:** https://policies.google.com/terms

Google's Gemini API documentation lists `gemini-nano-banana-2.1` as the model identifier for API use. This identifier is a reference only; this project did not call the API directly. Since this is a hosted model, this repository links to the official model card and terms rather than claiming an open-source checkpoint license.

## Contents
- `prompts.txt` — prepared set of 30 prompt themes.
- `generated_images/` — 30 generated image files.
- `inference_notes.txt` — workflow and reproducibility notes.
- `failure_analysis.txt` — qualitative review under 200 words.
- `examples/` — five selected image case studies.
- `contact_sheet.jpg` — visual index of all images.

## Safety statement
The prompt set uses generic scenes and does not intentionally request a named living artist's style, private personal information, or explicit sensitive content. Google Flow platform safety controls may apply. The author did not report configuring a separate custom safety filter. This describes the reported workflow and is not an independent audit of platform safety behavior.

## Limitations and final verification
The hosted interface may not expose all internal generation parameters. Some outputs appear thematically similar, and prompt-to-image matching must be checked against the original Flow session. `prompts.txt` reconstructs the previously prepared prompt list from its recorded themes; compare it with the original prompt block before submission if exact wording is required. Image files were renamed for organization; image pixels were not edited during packaging.
