# hugo-server-problem

On my mac M1 I have an issue when I run Hugo Server. If you clone this repo, and run `hugo server -D` the homepage will render. If you try and navigate to the URL `http://localhost:1313/transport/bus-stop-2/` the page will not render. The only way to get the page to render is but editing the contents and saving it. If I have (for example) 50 pages in the `contents/transport/` directory I'd have to open and save each one to get it to render.

I have tried different themes, different flags with `hugo server` such as `--disableFastRender` and nothing makes a difference. Is this a known issue or am I doing something wrong?

hugo version: `hugo v0.110.0+extended darwin/arm64 BuildDate=unknown`
MAC M1
