# gpt2txt

English | [中文](./README-CN.md)

Image to text using gpt, fast. Built with the [Vercel AI SDK](https://sdk.vercel.ai), [Claude](https://claude.ai/), and [Next.js](https://nextjs.org).

[![Deploy with Vercel](https://vercel.com/button)](https://vercel.com/new/clone?repository-url=https%3A%2F%2Fgithub.com%2Fzhiyu1998%2Fgpt2txt&env=OPENAI_BASE_URL,OPENAI_API_KEY,OPENAI_MODEL&envDescription=your%20OpenAI%20API%20key%20from%20OpenAI%20Platform%20or%20otherwise&envLink=https%3A%2F%2Fplatform.openai.com%2Fapi-keys&project-name=gpt2txt&repository-name=gpt2txt&demo-title=gpt2txt&demo-description=image%20to%20text%20using%20gpt%2C%20fast.&demo-url=https%3A%2F%2Fgpt2txt.vercel.app%2F&demo-image=https%3A%2F%2Fgpt2txt.vercel.app%2Fopengraph-image.png)

![home](./md-imgs/home.png)

## Developing

-   Clone the repository
-   Create a `.env.local` file with `OPENAI_API_KEY=your-api-key` 、 `OPENAI_BASE_URL=your-base-url` and `OPENAI_MODEL=your-like-model` where `your-api-key` is your OpenAI API key from [OpenAI Platform](https://platform.openai.com/api-keys).
-   Run `yarn` to install dependencies.
-   Run `yarn dev` to start the development server.

## Acknowledgments

Thanks to the 2txt framework created by ai-ng, I created gpt2txt because it was not convenient for me to purchase Claude's API:

- [2txt: Image to text, fast.](https://github.com/ai-ng/2txt)