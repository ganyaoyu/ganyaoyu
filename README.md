<details open>
<summary>English</summary>
<a name="english"></a>

~~~cpp
struct AboutMe
{
    const char *name { "Vivi" };
    const uint8_t age { 17 };
    const char *languages[7] {
        "C++",
        "C",
        "Rust",
        "Go",
        "Assembly",
        "Python",
        "Typescript",
    };
    const char *interests[4] {
        "Kernel Development",
        "Distributed Systems",
        "Backend Programming",
        "Low-latency Programming",
    };
    const char *hobbies[3] {
        "Reading Novels",
        "Cooking",
        "Gardening",
    };

    static constexpr size_t languagesCount { 7 };
    static constexpr size_t interestCount { 4 };
    static constexpr size_t hobbyCount { 3 };
};
~~~
</details>

<details>
<summary>中文</summary>
<a name="中文"></a>

~~~cpp
struct AboutMe
{
    const char *name { "耀宇" };
    const uint8_t age { 17 };
     const char *languages[7] {
        "C++",
        "C",
        "Rust",
        "Go",
        "Assembly",
        "Python",
        "Typescript",
    };
    const char *interests[4] {
        "内核开发",
        "分布式系统",
        "后端编程",
        "低延迟开发",
    };
    const char *hobbies[3] {
        "看小说",
        "做饭",
        "园艺",
    };

    static constexpr size_t languagesCount { 7 };
    static constexpr size_t interestCount { 4 };
    static constexpr size_t hobbyCount { 3 };
};
~~~
</details>
