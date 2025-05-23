# Compass Starter Stack Content

This repository aims to provide sample stack content with personalize project, experiences, audiences, attributes and variants to users for the implementation of compass starter app demo websites. An easy way to import this stack content is by using the ‘seed’ command.

### Note : Contentstack stack must have English as Master Language

To import this content to your stack, perform the following steps:

1. Install the CLI by running the following command in your terminal:

	```npm i -g @contentstack/cli@1.32.1``` 

2. By default, CLI uses the North America region. To use the Europe region, run this command in your terminal:

	```csdx config:set:region EU```

3. Next, log in to your Contentstack account via CLI:

	```csdx auth:login```

4. Run the ‘seed’ command to import content to your stack: 

	```csdx cm:stacks:seed --repo "contentstack/compass-starter-stack" --locale "en"```

Refer to the [Seed command documentation](https://www.contentstack.com/docs/developers/cli/import-content-using-the-seed-command/) to learn more. 

## Compass Starter App

### We have our own Next.js app where you can instantly view this content.

[Compass Starter Code Repo](https://github.com/contentstack/compass-starter-app)

## Documentation
- [Contentstack personalize documentation](https://www.contentstack.com/docs/personalize)

## Note
To work with Visual Builder, your Contentstack Organization must have appropriate plan enabled.

