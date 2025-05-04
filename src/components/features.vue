<template>
  <section class="features">
    <!-- Advanced AI Card -->
    <div class="feature-card">
      <div class="card-header">
        <div class="feature-icon">
          <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24" fill="none" stroke="currentColor"
            stroke-width="2" stroke-linecap="round" stroke-linejoin="round">
            <path d="M12 2a8 8 0 0 0-8 8c0 6 8 12 8 12s8-6 8-12a8 8 0 0 0-8-8zm0 11a3 3 0 1 1 0-6 3 3 0 0 1 0 6z" />
          </svg>
        </div>
        <h3>Advanced AI</h3>
      </div>
      <div class="card-body">
        <p>Cutting-edge neural networks that evolve with your interaction.</p>
        <ul>
          <li>Natural language understanding</li>
          <li>Behavioral learning</li>
          <li>Real-time adaptation</li>
        </ul>
      </div>
    </div>

    <!-- Smart Workspace -->
    <div class="feature-card">
      <div class="card-header">
        <div class="feature-icon">
          <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24" fill="none" stroke="currentColor"
            stroke-width="2" stroke-linecap="round" stroke-linejoin="round">
            <rect x="3" y="3" width="7" height="7" />
            <rect x="14" y="3" width="7" height="7" />
            <rect x="14" y="14" width="7" height="7" />
            <rect x="3" y="14" width="7" height="7" />
          </svg>
        </div>
        <h3>Smart Workspace</h3>
      </div>
      <div class="card-body">
        <p>A unified platform to think, write, and organize intelligently.</p>
        <ul>
          <li>AI-powered notes</li>
          <li>Real-time sync</li>
          <li>Focus & flow tools</li>
        </ul>
      </div>
    </div>

    <!-- Personalized Agents -->
    <div class="feature-card">
      <div class="card-header">
        <div class="feature-icon">
          <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24" fill="none" stroke="currentColor"
            stroke-width="2" stroke-linecap="round" stroke-linejoin="round">
            <path d="M20 21v-2a4 4 0 0 0-3-3.87" />
            <path d="M4 21v-2a4 4 0 0 1 3-3.87" />
            <circle cx="12" cy="7" r="4" />
          </svg>
        </div>
        <h3>Personalized Agents</h3>
      </div>
      <div class="card-body">
        <p>Trainable AI agents tailored to your tasks and style.</p>
        <ul>
          <li>Voice & chat interaction</li>
          <li>Custom memory</li>
          <li>Agent-to-agent collaboration</li>
        </ul>
      </div>
    </div>
  </section>
</template>

<style scoped>
.features {
  display: grid;
  gap: 2rem;
  grid-template-columns: repeat(auto-fit, minmax(280px, 1fr));
  padding: 3rem 1.5rem;
  background-color: #0e0e10;
}

.feature-card {
  background: #1a1a1d;
  border: 1px solid #2c2c2f;
  border-radius: 1rem;
  padding: 2rem;
  transition: transform 0.3s ease, box-shadow 0.3s ease;
  box-shadow: 0 0 0 transparent;
}

.feature-card:hover {
  transform: translateY(-5px);
  box-shadow: 0 8px 24px rgba(255, 255, 255, 0.08);
}

.card-header {
  display: flex;
  align-items: center;
  gap: 1rem;
  margin-bottom: 1rem;
}

.feature-icon {
  background: linear-gradient(135deg, #7f5af0, #2cb67d);
  border-radius: 0.75rem;
  padding: 0.75rem;
  display: flex;
  align-items: center;
  justify-content: center;
}

.feature-icon svg {
  color: white;
  width: 24px;
  height: 24px;
}

.card-header h3 {
  margin: 0;
  font-size: 1.25rem;
  color: #fff;
}

.card-body p {
  color: #b0b0b0;
  font-size: 0.95rem;
  line-height: 1.5;
  margin-bottom: 0.75rem;
}

.card-body ul {
  list-style: none;
  padding-left: 1rem;
  color: #dcdcdc;
  font-size: 0.9rem;
}

.card-body ul li::before {
  content: "•";
  color: #2cb67d;
  margin-right: 0.5rem;
}
</style>
