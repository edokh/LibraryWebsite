<template>
    <!-- component -->
    <section class="text-gray-700 body-font overflow-hidden bg-white">
        <div class="container px-5 py-24 mx-auto">
            <div class="lg:w-full mx-auto flex flex-wrap">
                <div class="lg:w-1/4 w-full h-full lg:p-8">
                    <img
                        alt="ecommerce"
                        class="
                            object-cover object-center
                            rounded
                            border border-gray-200
                            w-full
                        "
                        :src="
                            APP_URL + '/images/books_images/' + book.book_image
                        "
                    />
                </div>
                <div class="lg:w-1/2 w-full lg:pl-10 lg:py-6 mt-6 lg:mt-0">
                    <h2
                        class="text-sm title-font text-gray-500 tracking-widest"
                    >
                        {{ book.author }}
                    </h2>
                    <h1
                        class="
                            text-gray-900 text-3xl
                            title-font
                            font-medium
                            mb-1
                        "
                    >
                        {{ book.title }}
                    </h1>
                    <div class="flex mb-4">
                        <span class="flex items-center">
                            <svg
                                fill="currentColor"
                                stroke="currentColor"
                                stroke-linecap="round"
                                stroke-linejoin="round"
                                stroke-width="2"
                                class="w-4 h-4 text-orange-500"
                                viewBox="0 0 24 24"
                            >
                                <path
                                    d="M12 2l3.09 6.26L22 9.27l-5 4.87 1.18 6.88L12 17.77l-6.18 3.25L7 14.14 2 9.27l6.91-1.01L12 2z"
                                ></path>
                            </svg>
                            <svg
                                fill="currentColor"
                                stroke="currentColor"
                                stroke-linecap="round"
                                stroke-linejoin="round"
                                stroke-width="2"
                                class="w-4 h-4 text-orange-500"
                                viewBox="0 0 24 24"
                            >
                                <path
                                    d="M12 2l3.09 6.26L22 9.27l-5 4.87 1.18 6.88L12 17.77l-6.18 3.25L7 14.14 2 9.27l6.91-1.01L12 2z"
                                ></path>
                            </svg>
                            <svg
                                fill="currentColor"
                                stroke="currentColor"
                                stroke-linecap="round"
                                stroke-linejoin="round"
                                stroke-width="2"
                                class="w-4 h-4 text-orange-500"
                                viewBox="0 0 24 24"
                            >
                                <path
                                    d="M12 2l3.09 6.26L22 9.27l-5 4.87 1.18 6.88L12 17.77l-6.18 3.25L7 14.14 2 9.27l6.91-1.01L12 2z"
                                ></path>
                            </svg>
                            <svg
                                fill="currentColor"
                                stroke="currentColor"
                                stroke-linecap="round"
                                stroke-linejoin="round"
                                stroke-width="2"
                                class="w-4 h-4 text-orange-500"
                                viewBox="0 0 24 24"
                            >
                                <path
                                    d="M12 2l3.09 6.26L22 9.27l-5 4.87 1.18 6.88L12 17.77l-6.18 3.25L7 14.14 2 9.27l6.91-1.01L12 2z"
                                ></path>
                            </svg>
                            <svg
                                fill="none"
                                stroke="currentColor"
                                stroke-linecap="round"
                                stroke-linejoin="round"
                                stroke-width="2"
                                class="w-4 h-4 text-orange-500"
                                viewBox="0 0 24 24"
                            >
                                <path
                                    d="M12 2l3.09 6.26L22 9.27l-5 4.87 1.18 6.88L12 17.77l-6.18 3.25L7 14.14 2 9.27l6.91-1.01L12 2z"
                                ></path>
                            </svg>
                            <span class="text-gray-600 ml-3">4 مراجعات</span>
                        </span>
                        <span
                            class="
                                flex
                                ml-3
                                pl-3
                                py-2
                                border-l-2 border-gray-200
                            "
                        >
                            <a class="text-gray-500">
                                <svg
                                    fill="currentColor"
                                    stroke-linecap="round"
                                    stroke-linejoin="round"
                                    stroke-width="2"
                                    class="w-5 h-5"
                                    viewBox="0 0 24 24"
                                >
                                    <path
                                        d="M18 2h-3a5 5 0 00-5 5v3H7v4h3v8h4v-8h3l1-4h-4V7a1 1 0 011-1h3z"
                                    ></path>
                                </svg>
                            </a>
                            <a class="ml-2 text-gray-500">
                                <svg
                                    fill="currentColor"
                                    stroke-linecap="round"
                                    stroke-linejoin="round"
                                    stroke-width="2"
                                    class="w-5 h-5"
                                    viewBox="0 0 24 24"
                                >
                                    <path
                                        d="M23 3a10.9 10.9 0 01-3.14 1.53 4.48 4.48 0 00-7.86 3v1A10.66 10.66 0 013 4s-4 9 5 13a11.64 11.64 0 01-7 2c9 5 20 0 20-11.5a4.5 4.5 0 00-.08-.83A7.72 7.72 0 0023 3z"
                                    ></path>
                                </svg>
                            </a>
                            <a class="ml-2 text-gray-500">
                                <svg
                                    fill="currentColor"
                                    stroke-linecap="round"
                                    stroke-linejoin="round"
                                    stroke-width="2"
                                    class="w-5 h-5"
                                    viewBox="0 0 24 24"
                                >
                                    <path
                                        d="M21 11.5a8.38 8.38 0 01-.9 3.8 8.5 8.5 0 01-7.6 4.7 8.38 8.38 0 01-3.8-.9L3 21l1.9-5.7a8.38 8.38 0 01-.9-3.8 8.5 8.5 0 014.7-7.6 8.38 8.38 0 013.8-.9h.5a8.48 8.48 0 018 8v.5z"
                                    ></path>
                                </svg>
                            </a>
                        </span>
                    </div>
                    <p class="leading-relaxed">
                        {{ book.description }}
                    </p>
                    <div class="flex my-2">
                        <span
                            class="
                                title-font
                                font-medium
                                text-2xl text-gray-900
                            "
                            >{{ book.price + ' د.ع ' }}</span
                        >
                        <router-link
                            :to="{
                                name: 'orderForm',
                                params: {
                                    slug: book.slug,
                                },
                            }"
                            class="
                                flex
                                ml-auto
                                text-white
                                bg-orange-500
                                border-0
                                py-2
                                px-6
                                mr-2
                                focus:outline-none
                                hover:bg-orange-600
                                rounded
                            "
                        >
                            أطلب الآن
                        </router-link>
                        <button
                            class="
                                rounded-full
                                w-10
                                h-10
                                bg-gray-200
                                p-0
                                border-0
                                inline-flex
                                items-center
                                justify-center
                                text-gray-500
                                ml-4
                            "
                        >
                            <svg
                                fill="currentColor"
                                stroke-linecap="round"
                                stroke-linejoin="round"
                                stroke-width="2"
                                class="w-5 h-5"
                                viewBox="0 0 24 24"
                            >
                                <path
                                    d="M20.84 4.61a5.5 5.5 0 00-7.78 0L12 5.67l-1.06-1.06a5.5 5.5 0 00-7.78 7.78l1.06 1.06L12 21.23l7.78-7.78 1.06-1.06a5.5 5.5 0 000-7.78z"
                                ></path>
                            </svg>
                        </button>
                    </div>
                </div>
                <div class="lg:w-1/4 w-full lg:pl-10 lg:pt-36 lg:mt-0">
                    <ul class="text-right">
                        <li>
                            <label class="font-bold ml-2">اللغة:</label>
                            {{
                                book.language == 'arabic'
                                    ? 'العربية'
                                    : book.language == 'english'
                                    ? 'الأنكليزية'
                                    : 'الكوردية'
                            }}
                        </li>
                        <li>
                            <label class="font-bold ml-2">للمؤلف:</label>
                            {{ book.author }}
                        </li>
                        <li>
                            <label class="font-bold ml-2">عدد الصفحات:</label>
                            {{ book.pages }}
                        </li>
                        <li>
                            <label class="font-bold ml-2"
                                >النسخ المتوفرة:</label
                            >
                            {{ book.number_of_copies }}
                        </li>
                        <li>
                            <label class="font-bold ml-2">سنة النشر:</label>
                            {{ book.publication_year }}
                        </li>
                        <li>
                            <label class="font-bold ml-2">الفئة:</label>
                            {{ book.category }}
                        </li>
                    </ul>
                </div>
            </div>
        </div>
    </section>
</template>
<script>
import { onMounted } from '@vue/runtime-core'
import useBooks from '../../composables/books'
import { config } from '../../config'
export default {
    props: {
        slug: {
            default: 'book',
            type: String,
        },
    },
    setup(props) {
        const { getBook, book } = useBooks()
        onMounted(async () => {
            await getBook(props.slug)
        })

        return { book, APP_URL: config.APP_URL }
    },
}
</script>