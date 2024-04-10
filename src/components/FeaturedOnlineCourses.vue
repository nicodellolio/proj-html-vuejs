<script>
export default {
    name: 'FeaturedOnlineCourses',
    components: {
    },

    data() {
        return {
        }
    }
}
</script>

<template>
    <section class="FeOnCo">
        <div class="FeOnCo-head">
            <h5>Stimulated to learn?</h5>
            <h1>Featured Online Courses</h1>
        </div>
        <div class="FeOnCo-courses">
            <div class="course">
                <div class="course-img c-i-tl"></div>
                <div class="course-text">
                    <h2>$40</h2>
                    <h3>.00</h3>

                    <p class="course-description">
                        Learning to Write as a Professional Author
                    </p>
                    <span>
                        <i class="fa-regular fa-file-lines"></i>
                        20 Lessons
                    </span>
                    <span>
                        <i class="fa-regular fa-file-lines"></i>
                        50 Students
                    </span>
                </div>
            </div>
            <div class="course">
                <div class="course-img c-i-tr"></div>
                <div class="course-text">
                    <h2>Free</h2>

                    <p class="course-description">
                        Customer-centric Info-Tech Strategies
                    </p>
                    <span>
                        <i class="fa-regular fa-file-lines"></i>
                        24 Lessons
                    </span>
                    <span>
                        <i class="fa-regular fa-file-lines"></i>
                        769 Students
                    </span>
                </div>
            </div>
            <div class="course">
                <div class="course-img c-i-ml"></div>
                <div class="course-text">
                    <h2>$19</h2>
                    <h3>.00</h3>

                    <p class="course-description">
                        Open Programming Courses for Everyone: Phyton
                    </p>
                    <span>
                        <i class="fa-regular fa-file-lines"></i>
                        17 Lessons
                    </span>
                    <span>
                        <i class="fa-regular fa-file-lines"></i>
                        62 Students
                    </span>
                </div>
            </div>
            <div class="course">
                <div class="course-img c-i-mr"></div>
                <div class="course-text">
                    <h2>$26</h2>
                    <h3>.00</h3>

                    <p class="course-description">
                        Academic Listening and Note-taking
                    </p>
                    <span>
                        <i class="fa-regular fa-file-lines"></i>
                        14 Lessons
                    </span>
                    <span>
                        <i class="fa-regular fa-file-lines"></i>
                        67 Students
                    </span>
                </div>
            </div>
            <div class="course">
                <div class="course-img c-i-bl"></div>
                <div class="course-text">
                    <h2>$39</h2>
                    <h3>.00</h3>

                    <p class="course-description">
                        Master jQuery in a Short Period of Time
                    </p>
                    <span>
                        <i class="fa-regular fa-file-lines"></i>
                        6 Lessons
                    </span>
                    <span>
                        <i class="fa-regular fa-file-lines"></i>
                        51 Students
                    </span>
                </div>
            </div>
            <div class="course">
                <div class="course-img c-i-br"></div>
                <div class="course-text">
                    <h2>$59</h2>
                    <h3>.00</h3>

                    <p class="course-description">
                        Introducing to Javascript for Beginners
                    </p>
                    <span>
                        <i class="fa-regular fa-file-lines"></i>
                        14 Lessons
                    </span>
                    <span>
                        <i class="fa-regular fa-file-lines"></i>
                        76 Students
                    </span>
                </div>
            </div>

        </div>
        <button>View all courses
            <i class="fa fa-arrow-right" aria-hidden="true"></i>
        </button>
    </section>

</template>

<style lang="css">
    @import url(/src/assets/partials/css/FeOnCo.css);
</style>