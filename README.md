# npm-vorlage


<!-- Add copy year -->

    <script>
      document.querySelector('.js-data').textContent = new Date().getFullYear();
    </script>


<!-- Current month and year -->

    <script>
        const yearNumbers = document.querySelector(".year")
        const monthNumbers = document.querySelector(".month")

        const year = new Date().getFullYear();
        const month = new Date().getMonth();

        let currentMonth = month + 1;

        if (currentMonth === 13) {
            currentMonth = 1
        }

        yearNumbers.textContent = year
        monthNumbers.textContent = currentMonth
    </script>