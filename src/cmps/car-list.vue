<template>
    <section class="car-list">
        <h1>Cars</h1>
        <pre>{{cars}}</pre>
    </section>
</template>

<script>
    export default {
        data() {
            return {
                cars: [
                    { id: '101', name: 'Subali', speed: 100 },
                    { id: '102', name: 'Fiak', speed: 140 },
                    { id: '103', name: 'Toyoka', speed: 90 },
                    { id: '104', name: 'Audo', speed: 20 },
                ]
            }
        }
    }
</script>