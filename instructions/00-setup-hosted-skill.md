# Hello World Skill Creation

You will create and test your First Alexa Skill fully from the [Alexa Developer Console](https://developer.amazon.com/alexa/console/ask).

1. Navigate to the [Alexa Developer Console](https://developer.amazon.com/alexa/console/ask) 

![console](./images/alexa_developer_console.png)

2. Create a new Custom Skill with `Alexa-Hosted` for your backend resources

![hosted](./images/custom_hosted_skill_creation.png)

3. On the `Build` Tab of your Skill, click on `JSON Editor` and copy-paste [this interaction model](https://raw.githubusercontent.com/nachawat/skill-sample-nodejs-helloworld-fr/master/models/fr-FR.json)

![hosted](./images/interaction_model.png)

4. Save your Interaction Model

![save](./images/todo_save_model.png)

>  **Important**: The developer console does not automatically save your work as you make changes. If you close the browser window without clicking Save Model, your work is lost.

5. Build your Interaction Model

![save](./images/todo_build_model.png)

> **Important**: You must successfully build the model before you can test it.

### Bravo ! You have just created your first Interaction Model. Now, you will create your Skill backend.

6. Navigate to `Code` Tab and copy-paste [this backend code](https://github.com/nachawat/skill-sample-nodejs-helloworld-fr/blob/master/lambda/custom/index.js)

![backend](./images/backend_hosted_skill.png)

7. Save your code

![save_backend](./images/save_backend.png)

>  **Important**: The developer console does not automatically save your work as you make changes. If you close the browser window without clicking Save, your work is lost.

8. Deploy your code

![deploy_backend](./images/deploy_backend.png)

> **Important**: You must successfully deploy the code before you can test it.

### Bravo ! You have just created your first Skill backend from the Alexa Developer Console using Alexa Skill Kit (ASK) SDKv2 for Node.js. Now, you will test your Skill backend.

9. Navigate to the `Test` Tab and enter the following utterance in the simulator ```ouvre mon atelier```

![skill_test_simulator](./images/skill_test_simulator.png)

## Bravo ! You have just created and tested your First Alexa Skill using Hosted Skill.

