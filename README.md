# napkin-chat

>Note: This repo has value for you, if you have a Napkin account and already saved some quotes.

### Goal of this Repo
1. Utilize personal quotes from [Napkin](https://napkin.one) to augment the responses from a LLM.
2. Having the ability to rate the augmented response in comparison to the "normal" response.
3. Persist the ratings and their respective Question/Answer pairs, to build a dataset for future use.
4. Can be run fully local.
5. Supports OpenAI like Chat Endpoints.
6. Clean Gradio Interface.

### How to use this setup
1. Login to the [Napkin App](https://app.napkin.one)
2. Click on the Manikin/Person Icon in the top right corner. The "your account" menu/window should open.
3. Under **Export** click on *Export JSON*. One click is enough. This might take a couple of minutes until the file is downloaded.
4. Save the file within this repository.

-> Everything else will follow once, developed.

##### Further Developments
- Dockerize, so that a full container can be downloaded.
- Drag&Drop the JSON File, so there is no need for volume mounting of the Export Files.