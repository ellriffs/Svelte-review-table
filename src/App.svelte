<script>
  import FeedbackForm from './components/FeedbackForm.svelte';
  import FeedbackList from './components/FeedbackList.svelte';
  import FeedbackStats from './components/FeedbackStats.svelte';
  import Header from './components/Header.svelte';
</script>

<main class="container">
  <Header />
  <FeedbackForm />
  <FeedbackStats />
  <FeedbackList />
</main>
