<template>
  <Layout class="bg-dark text-white relative">
    <section
      id="introduction"
      class="min-h-screen  relative overflow-hidden z-20 px-2"
    >
      <!-- The top left ring -->
      <div
        class="absolute top-0 left-0 h-64 w-64 rounded-full border-4 border-red-600 -mt-48 -ml-32"
      >
        &nbsp;
      </div>

      <!-- The top right solid circle -->
      <div
        class="z-20 absolute top-0 right-0 h-64 w-64 md:h-160 md:w-160 rounded-full bg-gradient-to-b via-red-600 from-pink-600 to-dark -mt-16 -mr-24 md:-mt-32 md:-mr-48"
      >
        <g-image
          src="@/kp.png"
          class="-mb-24 md:-mb-52 mr-24 md:mr-32 w-44 md:w-96 absolute bottom-0 right-0"
        />
      </div>

      <!-- The hero section -->
      <div class="px-4 pt-80 md:pt-36 container mx-auto md:text-lg">
        <!-- logo -->
        <div class="flex items-end text-red-600 text-xl md:text-4xl font-medium">
          <div class="flex items-end">
            <div
              class="relative z-20 h-6 w-6 rounded-full bg-red-600 font-bold text-black flex items-center justify-center uppercase text-sm"
            >
              kp
            </div>
            <div
              class="relative z-10 h-6 w-6 md:h-8 md:w-8 rounded-full border-2 border-red-600 -ml-2 md:-ml-4"
            ></div>
          </div>
          <span class="ml-1 -mb-1">kudapara</span>
        </div>

        <!-- Name -->
        <h1 class="text-2xl md:text-6xl font-black text-white mb-4">
          Kudakwashe Paradzayi
        </h1>
        <h2 class="text-xl md:text-3xl text-white mb-2">
          Designer &middot; Software Engineer &middot; Nerd
        </h2>
        <span class="text-base text-gray-200"
          >Currently bringing fresh ideas to life.
          <a href="https://freshideas.co.zw" class="text-red-600 text-base">Learn more.</a></span
        >

        <!-- Call to action -->
        <div class="flex items-center justify-between md:max-w-lg mt-16">
          <a
            href="https://twitter.com/intent/follow?screen_name=kudapara"
            class="w-full md:w-auto text-center block bg-red-600 text-white py-4 px-16 hover:bg-red-700 hover:shadow-lg"
            >Follow me on twitter</a
          >
        </div>
      </div>

      <div class="container mx-auto pt-16">
        <div
          class="h-1 bg-red-600 bg-gradient-to-r from-red-600 to-dark max-w-4xl"
        ></div>

        <!-- Links to other parts of the site -->
        <ul v-if="false" class="mt-8 flex flex-wrap max-w-lg">
          <li class="w-1/2 py-2 border-b border-gray-800">
            <a
              href="/blog"
              class="flex items-center justify-between w-48 py-2 px-4 hover:bg-darktransparent rounded-lg"
            >
              <div class="flex items-center space-x-2">
                <svg
                  class="w-4 h-4 text-red-600"
                  fill="currentColor"
                  viewBox="0 0 20 20"
                  xmlns="http://www.w3.org/2000/svg"
                >
                  <path
                    fill-rule="evenodd"
                    d="M11.3 1.046A1 1 0 0112 2v5h4a1 1 0 01.82 1.573l-7 10A1 1 0 018 18v-5H4a1 1 0 01-.82-1.573l7-10a1 1 0 011.12-.38z"
                    clip-rule="evenodd"
                  ></path>
                </svg>
                <span>Blog</span>
              </div>

              <svg
                class="w-6 h-6"
                fill="currentColor"
                viewBox="0 0 20 20"
                xmlns="http://www.w3.org/2000/svg"
              >
                <path
                  fill-rule="evenodd"
                  d="M7.293 14.707a1 1 0 010-1.414L10.586 10 7.293 6.707a1 1 0 011.414-1.414l4 4a1 1 0 010 1.414l-4 4a1 1 0 01-1.414 0z"
                  clip-rule="evenodd"
                ></path>
              </svg>
            </a>
          </li>
          <li class="w-1/2 py-2 border-b border-gray-800">
            <a
              href="/blog"
              class="flex items-center justify-between w-48 py-2 px-4 hover:bg-darktransparent rounded-lg"
            >
              <div class="flex items-center space-x-2">
                <svg
                  class="w-4 h-4 text-red-600"
                  fill="currentColor"
                  viewBox="0 0 20 20"
                  xmlns="http://www.w3.org/2000/svg"
                >
                  <path
                    fill-rule="evenodd"
                    d="M11.3 1.046A1 1 0 0112 2v5h4a1 1 0 01.82 1.573l-7 10A1 1 0 018 18v-5H4a1 1 0 01-.82-1.573l7-10a1 1 0 011.12-.38z"
                    clip-rule="evenodd"
                  ></path>
                </svg>
                <span>Twitter</span>
              </div>

              <svg
                class="w-6 h-6"
                fill="currentColor"
                viewBox="0 0 20 20"
                xmlns="http://www.w3.org/2000/svg"
              >
                <path
                  fill-rule="evenodd"
                  d="M7.293 14.707a1 1 0 010-1.414L10.586 10 7.293 6.707a1 1 0 011.414-1.414l4 4a1 1 0 010 1.414l-4 4a1 1 0 01-1.414 0z"
                  clip-rule="evenodd"
                ></path>
              </svg>
            </a>
          </li>
          <li class="w-1/2 py-2 border-b border-gray-800">
            <a
              href="/blog"
              class="flex items-center justify-between w-48 py-2 px-4 hover:bg-darktransparent rounded-lg"
            >
              <div class="flex items-center space-x-2">
                <svg
                  class="w-4 h-4 text-red-600"
                  fill="currentColor"
                  viewBox="0 0 20 20"
                  xmlns="http://www.w3.org/2000/svg"
                >
                  <path
                    fill-rule="evenodd"
                    d="M11.3 1.046A1 1 0 0112 2v5h4a1 1 0 01.82 1.573l-7 10A1 1 0 018 18v-5H4a1 1 0 01-.82-1.573l7-10a1 1 0 011.12-.38z"
                    clip-rule="evenodd"
                  ></path>
                </svg>
                <span>Projects</span>
              </div>

              <svg
                class="w-6 h-6"
                fill="currentColor"
                viewBox="0 0 20 20"
                xmlns="http://www.w3.org/2000/svg"
              >
                <path
                  fill-rule="evenodd"
                  d="M7.293 14.707a1 1 0 010-1.414L10.586 10 7.293 6.707a1 1 0 011.414-1.414l4 4a1 1 0 010 1.414l-4 4a1 1 0 01-1.414 0z"
                  clip-rule="evenodd"
                ></path>
              </svg>
            </a>
          </li>
          <li class="w-1/2 py-2 border-b border-gray-800">
            <a
              href="/blog"
              class="flex items-center justify-between w-48 py-2 px-4 hover:bg-darktransparent rounded-lg"
            >
              <div class="flex items-center space-x-2">
                <svg
                  class="w-4 h-4 text-red-600"
                  fill="currentColor"
                  viewBox="0 0 20 20"
                  xmlns="http://www.w3.org/2000/svg"
                >
                  <path
                    fill-rule="evenodd"
                    d="M11.3 1.046A1 1 0 0112 2v5h4a1 1 0 01.82 1.573l-7 10A1 1 0 018 18v-5H4a1 1 0 01-.82-1.573l7-10a1 1 0 011.12-.38z"
                    clip-rule="evenodd"
                  ></path>
                </svg>
                <span>Github</span>
              </div>

              <svg
                class="w-6 h-6"
                fill="currentColor"
                viewBox="0 0 20 20"
                xmlns="http://www.w3.org/2000/svg"
              >
                <path
                  fill-rule="evenodd"
                  d="M7.293 14.707a1 1 0 010-1.414L10.586 10 7.293 6.707a1 1 0 011.414-1.414l4 4a1 1 0 010 1.414l-4 4a1 1 0 01-1.414 0z"
                  clip-rule="evenodd"
                ></path>
              </svg>
            </a>
          </li>
          <li class="w-1/2 py-2">
            <a
              href="/blog"
              class="flex items-center justify-between w-48 py-2 px-4 hover:bg-darktransparent rounded-lg"
            >
              <div class="flex items-center space-x-2">
                <svg
                  class="w-4 h-4 text-red-600"
                  fill="currentColor"
                  viewBox="0 0 20 20"
                  xmlns="http://www.w3.org/2000/svg"
                >
                  <path
                    fill-rule="evenodd"
                    d="M11.3 1.046A1 1 0 0112 2v5h4a1 1 0 01.82 1.573l-7 10A1 1 0 018 18v-5H4a1 1 0 01-.82-1.573l7-10a1 1 0 011.12-.38z"
                    clip-rule="evenodd"
                  ></path>
                </svg>
                <span>About Me</span>
              </div>

              <svg
                class="w-6 h-6"
                fill="currentColor"
                viewBox="0 0 20 20"
                xmlns="http://www.w3.org/2000/svg"
              >
                <path
                  fill-rule="evenodd"
                  d="M7.293 14.707a1 1 0 010-1.414L10.586 10 7.293 6.707a1 1 0 011.414-1.414l4 4a1 1 0 010 1.414l-4 4a1 1 0 01-1.414 0z"
                  clip-rule="evenodd"
                ></path>
              </svg>
            </a>
          </li>
          <li class="w-1/2 py-2">
            <a
              href="/blog"
              class="flex items-center justify-between w-48 py-2 px-4 hover:bg-darktransparent rounded-lg"
            >
              <div class="flex items-center space-x-2">
                <svg
                  class="w-4 h-4 text-red-600"
                  fill="currentColor"
                  viewBox="0 0 20 20"
                  xmlns="http://www.w3.org/2000/svg"
                >
                  <path
                    fill-rule="evenodd"
                    d="M11.3 1.046A1 1 0 0112 2v5h4a1 1 0 01.82 1.573l-7 10A1 1 0 018 18v-5H4a1 1 0 01-.82-1.573l7-10a1 1 0 011.12-.38z"
                    clip-rule="evenodd"
                  ></path>
                </svg>
                <span>Substack</span>
              </div>

              <svg
                class="w-6 h-6"
                fill="currentColor"
                viewBox="0 0 20 20"
                xmlns="http://www.w3.org/2000/svg"
              >
                <path
                  fill-rule="evenodd"
                  d="M7.293 14.707a1 1 0 010-1.414L10.586 10 7.293 6.707a1 1 0 011.414-1.414l4 4a1 1 0 010 1.414l-4 4a1 1 0 01-1.414 0z"
                  clip-rule="evenodd"
                ></path>
              </svg>
            </a>
          </li>
        </ul>
      </div>
    </section>

    <!-- The bubbles that show my interests -->
    <ul class="scroll js-homepage-bubble z-10">
      <li
        class="text"
        style="
          position: absolute;
          top: -30.0125px;
          transform-origin: 50% 50%;
          opacity: 0;
          transition: none 0s ease 0s;
          left: -101.973px;
          transform: translate(208.973px, 759.612px) rotate(2.3deg);
        "
      >
        Software Engineer
      </li>
      <li
        class="text"
        style="
          position: absolute;
          top: -32.972px;
          transform-origin: 50% 50%;
          opacity: 0;
          transition: none 0s ease 0s;
          left: -129.77px;
          transform: translate(129.77px, 756.653px) rotate(1.6deg);
        "
      >
        UI/UX Designer
      </li>
      <li
        class="text"
        style="
          position: absolute;
          top: -30.371px;
          transform-origin: 50% 50%;
          opacity: 0;
          transition: none 0s ease 0s;
          left: -124.428px;
          transform: translate(177.428px, 759.254px) rotate(-3.6deg);
        "
      >
        Crypto Enthusiast
      </li>
      <li
        class="text"
        style="
          position: absolute;
          top: -30.8746px;
          transform-origin: 50% 50%;
          opacity: 0;
          transition: none 0s ease 0s;
          left: -126.661px;
          transform: translate(179.661px, 758.75px) rotate(-2deg);
        "
      >
        Digital Artist
      </li>
      <li
        class="text"
        style="
          position: absolute;
          top: -27.7036px;
          transform-origin: 50% 50%;
          opacity: 0;
          transition: none 0s ease 0s;
          left: -115.341px;
          transform: translate(168.341px, 761.921px) rotate(3.1deg);
        "
      >
        The design guy
      </li>
      <li
        class="text"
        style="
          position: absolute;
          top: -27.3162px;
          transform-origin: 50% 50%;
          opacity: 0;
          transition: none 0s ease 0s;
          left: -93.8683px;
          transform: translate(98.8683px, 762.309px) rotate(2.6deg);
        "
      >
        Blockchain curious
      </li>
      <li
        class="text"
        style="
          position: absolute;
          top: -29.7394px;
          transform-origin: 50% 50%;
          opacity: 0;
          transition: none 0s ease 0s;
          left: -133.522px;
          transform: translate(140.522px, 759.886px) rotate(0.7deg);
        "
      >
        Team Player
      </li>
      <li
        class="brand flex space-x-2 text-sm"
        style="
          position: absolute;
          top: -35.061px;
          transform-origin: 50% 50%;
          opacity: 0;
          transition: none 0s ease 0s;
          left: -35.061px;
          transform: translate(67.061px, 754.564px) rotate(3.3deg);
        "
      >
        <img src="https://res.cloudinary.com/fresh-ideas/image/upload/v1599047512/Joeys_logo_d7grq3.svg" alt="" class="w-12">
        <span>joeys.co.zw</span>
      </li>
      <li
        class="brand flex space-x-2 text-sm"
        style="
          position: absolute;
          top: -35.1219px;
          transform-origin: 50% 50%;
          opacity: 0;
          transition: none 0s ease 0s;
          left: -35.122px;
          transform: translate(160.122px, 754.503px) rotate(1.8deg);
        "
      >
        <img src="https://res.cloudinary.com/fresh-ideas/image/upload/v1593878328/Mobile/Leaves_yase5z.svg" alt="" class="w-12">
        <span>freshinabox.co.zw</span>
      </li>
      <li
        class="brand flex space-x-2 text-sm"
        style="
          position: absolute;
          top: -35.061px;
          transform-origin: 50% 50%;
          opacity: 0;
          transition: none 0s ease 0s;
          left: -35.061px;
          transform: translate(113.061px, 754.564px) rotate(0.6deg);
        "
      >
        <img src="https://res.cloudinary.com/fresh-ideas/image/upload/v1612788463/logos/Fresh-Ideas-Logo_es5r47.png" alt="" class="w-12">
        <span>freshideas.co.zw</span>
      </li>
      <li
        class="brand flex space-x-2 text-sm"
        style="
          position: absolute;
          top: -36.9567px;
          transform-origin: 50% 50%;
          opacity: 0;
          transition: none 0s ease 0s;
          left: -36.9567px;
          transform: translate(194.957px, 752.668px) rotate(1.9deg);
        "
      >
      
      <img src="https://res.cloudinary.com/fresh-ideas/image/upload/v1600246342/bottlestore_lanscape_boqqzw.svg" alt="" class="h-12">

      </li>
    </ul>
  </Layout>
</template>

<script>
import dynamicProperties from "dynamic-properties";
export default {
  metaInfo: {
    title: "Kudakwashe Paradzayi",
  },

  mounted() {
    this.setupHomepageBubble();
  },

  methods: {
    setupHomepageBubble() {
      console.log('setting up the homepage bubble')
      const component = document.querySelector(".js-homepage-bubble");

      if (!component) {
        return;
      }

      const dimensions = dynamicProperties({
        viewportWidth: () => component.getBoundingClientRect().width,
        viewportHeight: () => component.getBoundingClientRect().height,
      });

      const items = Array.from(component.children);

      // Hide everything
      items.forEach((item) => {
        Object.assign(item.style, {
          position: "absolute",
          top: "100%",
          transformOrigin: "50% 50%",
          opacity: 0,
          transition: "none",
        });
      });

      // Options
      const options = {
        delayBetweenItems: 666,
        maximumItemsInViewport: 12,
        durationBounds: [10000, 20000],
      };

      if (!"animate" in document.body) {
        // Fallback
        const fallbackItems = items
          .map((item) => ({ item, sort: Math.random() }))
          .sort(({ sort: a }, { sort: b }) => a - b)
          .map(({ item }) => item)
          .slice(0, options.maximumItemsInViewport);

        const positions = [];

        const getRandomPosition = ({ width, height }) => {
          const x =
            width / 2 +
            Math.floor(Math.random() * (dimensions.viewportWidth - width));
          const y =
            height / 2 +
            Math.floor(Math.random() * (dimensions.viewportHeight - height));

          return {
            x,
            y,
            width,
            height,
          };
        };

        const hasOverlap = (position, positions) => {
          const overlapMargin = 20; // Making this too high can cause the whole thing to crash

          return positions.some(({ x, y, width, height }) => {
            const minX = x - width / 2 - overlapMargin;
            const maxX = x + width / 2 + overlapMargin;
            const minY = y - height / 2 - overlapMargin;
            const maxY = y + height / 2 + overlapMargin;

            // B's X is right of A's X
            if (position.x - position.width / 2 > maxX) {
              return false;
            }

            // B's X is left of A's X
            if (position.x + position.width / 2 < minX) {
              return false;
            }

            // B's X is right of A's X
            if (position.y - position.height / 2 > maxY) {
              return false;
            }

            // B's X is left of A's X
            if (position.y + position.height / 2 < minY) {
              return false;
            }

            return true;
          });
        };

        fallbackItems.forEach((item) => {
          const { width, height } = item.getBoundingClientRect();

          let position;
          let tries = 0; // Limit number of tries to avoid infinite loops :-)

          do {
            tries++;
            position = getRandomPosition({ width, height });
          } while (tries < 1000 && hasOverlap(position, positions));

          positions.push(position);

          const rotate = Math.round(-40 + Math.random() * 80) / 10;

          Object.assign(item.style, {
            top: `${-1 * (height / 2)}px`,
            left: `${-1 * (width / 2)}px`,
            transform: `translate(${position.x}px, ${position.y}px) rotate(${rotate}deg)`,
            opacity: 1,
          });
        });

        // Fallback finished, quit here
        return;
      }

      // Prototype bubble
      let queue = [...items];
      let currentlyBubbling = 0;
      let pool = [];

      const launchBubble = () => {
        const [item] = queue.splice(
          Math.floor(Math.random() * queue.length),
          1
        );

        // Place
        const { width, height } = item.getBoundingClientRect();
        const startX =
          width / 2 +
          Math.floor(Math.random() * (dimensions.viewportWidth - width));
        const startY = dimensions.viewportHeight - height / 2;
        const startRotate = Math.round(-40 + Math.random() * 80) / 10;

        const deltaX = Math.round(Math.random() * (2 * width) - width);
        const deltaRotate = Math.round(-300 + Math.random() * 600) / 10;

        const endX = startX + deltaX;
        const endY = -1 * Math.max(height, width / 2); // half width to account for rotation (it rotated 90deg,)
        const endRotate = startRotate + deltaRotate;

        const [minDuration, maxDuration] = options.durationBounds;
        const duration =
          minDuration + Math.floor(Math.random() * (maxDuration - minDuration));

        Object.assign(item.style, {
          top: `${-1 * (height / 2)}px`,
          left: `${-1 * (width / 2)}px`,
          transform: `translate(${startX}px, ${startY}px) rotate(${startRotate}deg)`,
          opacity: 0,
        });

        currentlyBubbling++;

        item
          .animate(
            [
              {
                transform: `translate(${startX}px, ${startY}px) rotate(${startRotate}deg) scale(0.825)`,
                opacity: 0,
              },
              { opacity: 0, offset: 0.025, easing: "linear" },
              { opacity: 1, offset: 0.15, easing: "linear" },
              { opacity: 1, offset: 0.75, easing: "linear" },
              {
                transform: `translate(${endX}px, ${endY}px) rotate(${endRotate}deg) scale(1.125)`,
                opacity: 0,
              },
            ],
            {
              duration,
              easing: "ease-in",
            }
          )
          .finished.then(() => {
            currentlyBubbling--;
            pool.push(item);
          });
      };

      const runtime = () => {
        if (queue.length === 0) {
          queue = pool;
          pool = [];
        }

        if (currentlyBubbling < options.maximumItemsInViewport) {
          launchBubble();
        }

        setTimeout(() => runtime(), options.delayBetweenItems);
      };

      runtime();
    },
  },
};
</script>


<style scoped>
.scroll {
  position: absolute;
  right: 0;
  top: 0;
  bottom: 0;
  width: 100%;
  list-style: none;
  margin: 0;
  padding: 0;
  opacity: 0.3;
}

.scroll li {
  background-color: #111015;
  border-radius: 20px;
  border-bottom-right-radius: 5px;
  display: inline;
  padding: 15px 20px;
  font-size: 1.05em;
  white-space: nowrap;
  overflow-y: hidden;
  opacity: 0;
  position: absolute;
  top: 0;
  left: 0;
}

.scroll .brand {
    border-radius: 100px;
    box-sizing: border-box;
    display: flex;
    align-items: center;
    justify-content: center;
    line-height: 1;

}
</style>