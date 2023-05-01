# X.RetroGameAIRemaster
Retro Game AI Remaster 🕹️: Stable Diffusion and SAM powered 🚀 console game upscaling 📈👾.

Introducing the Retro Game AI Remaster: a revolutionary tool that breathes new life into classic games from the NES-PSX era by employing modern AI technology to redraw their sprites in stunning 4K resolution.

Remember the days when games were simple and fun, without the constant pressure of in-app purchases and reward feedback loops? Back then, those 16x16, 8-color sprites were considered technological marvels. Wouldn't it be great to share the joy and nostalgia of those classic games with a new generation who may be more accustomed to photorealistic 4K gaming and the profit-driven tactics of modern game publishing companies? With the Retro Game AI Remaster, we can bridge the gap between past and present, and bring the magic of retro gaming to a whole new audience.

![image](https://user-images.githubusercontent.com/309302/233408074-d976230b-1f7b-4f3c-810a-f2bef5bc0a95.png)

![image](https://user-images.githubusercontent.com/309302/233408198-76947315-c1c7-48cd-9bc0-c96a9bda30f7.png)



## implentation

1. Firstly, we will fork https://www.webrcade.com and add:
  a) Screen segmentation (upon manual request) through Segment Anything to split the screen into sprites.
  b) The use of Stable Diffusion for upscaling individual sprites on the server.
  c) Buttons on each sprite to improve unsatisfactory outcomes.
  d) Loading pre-generated 4k sprites and overlaying them on the game screen.
At this point, retro games will be playable with the upscaled quality. However, we won't stop there and move to the next stage:
2. We will develop a native application for Mac and Windows that will run optimized models trained on data gathered in stage 1

![12](https://user-images.githubusercontent.com/309302/233406312-8516c24f-f004-472d-b745-a3f2e0955d04.jpeg)

![11](https://user-images.githubusercontent.com/309302/233406331-e5a3705a-e737-4927-b3bc-6d078aad95d4.png)


https://www.reddit.com/r/StableDiffusion/comments/11byv0o/the_game_doom_is_changing_with_controlnet_ebsynth/



![2](https://user-images.githubusercontent.com/309302/233405774-40ec0ee6-7030-485f-bc40-e515a9ebb99f.jpeg)


![5](https://user-images.githubusercontent.com/309302/233405824-7480e3d4-8c9b-4a02-a4a1-64cd120e9626.jpg)

![4](https://user-images.githubusercontent.com/309302/233405854-e88d048d-beb7-450b-8231-4e68b2a1d8ba.jpg)


### Segment Anything Screenshot Inference

<img width="898" alt="Screenshot 2023-05-02 at 1 35 12 AM" src="https://user-images.githubusercontent.com/309302/235544236-2b66e479-700b-4027-9d89-e7f5de45cec1.png">


<img width="809" alt="Screenshot 2023-05-02 at 1 41 34 AM" src="https://user-images.githubusercontent.com/309302/235544246-81e3b93d-0fa3-4c83-8305-7df92f9c55c5.png">


<img width="795" alt="Screenshot 2023-05-02 at 1 36 24 AM" src="https://user-images.githubusercontent.com/309302/235544275-52281cfa-585b-44f8-9c66-0e3b359a60cd.png">


<img width="648" alt="Screenshot 2023-05-02 at 1 40 18 AM" src="https://user-images.githubusercontent.com/309302/235544287-3a1dfea6-50fa-4cdf-af2f-a0a89d6697a4.png">

<img width="792" alt="Screenshot 2023-05-02 at 1 35 57 AM" src="https://user-images.githubusercontent.com/309302/235544302-77153715-28cd-4fa6-9dd7-f4e6f51533de.png">

<img width="669" alt="Screenshot 2023-05-02 at 1 41 01 AM" src="https://user-images.githubusercontent.com/309302/235544323-31dd660b-a487-43d9-8551-5bba847366ef.png">








