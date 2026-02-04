<script lang="ts">
</script>

<section id="contact" class="relative bg-gray-50 py-32">
  <div class="container mx-auto px-8 md:px-16 max-w-7xl">
    <div class="grid grid-cols-1 lg:grid-cols-2 gap-20">
      <!-- Left: Content -->
      <div>
        <span class="text-xs font-light tracking-[0.2em] text-primary-700 uppercase mb-6 block">Begin the Conversation</span>
        <h2 class="text-4xl md:text-5xl font-light text-gray-900 mb-8 leading-tight">
          Your family's legacy deserves thoughtful stewardship
        </h2>
        <p class="text-lg font-light text-gray-600 leading-relaxed mb-12">
          We work with a select number of families who value both tradition and innovation. If you're seeking a wealth management partner who understands the complexities of preserving legacy across generations, we invite you to begin a conversation.
        </p>

        <!-- Contact Information -->
        <div class="space-y-8">
          <div class="border-l-2 border-primary-700 pl-6">
            <div class="text-sm font-light tracking-wide text-gray-500 uppercase mb-2">For New Clients</div>
            <a href="mailto:inquiries@atlas.com" class="text-xl font-light text-gray-900 hover:text-primary-800 transition-colors">
              inquiries@atlas.com
            </a>
          </div>

          <div class="border-l-2 border-primary-700 pl-6">
            <div class="text-sm font-light tracking-wide text-gray-500 uppercase mb-2">Office</div>
            <div class="text-xl font-light text-gray-900">
              New York, NY
            </div>
          </div>
        </div>
      </div>

      <!-- Right: Form -->
      <div class="bg-white p-12 border border-gray-300">
        <form class="space-y-8">
          <div>
            <label for="name" class="block text-sm font-light tracking-wide text-gray-700 uppercase mb-3">
              Full Name
            </label>
            <input 
              type="text" 
              id="name" 
              name="name"
              class="w-full px-4 py-3 bg-gray-50 border border-gray-300 text-gray-900 font-light focus:outline-none focus:border-primary-700 transition-colors"
              required
            />
          </div>

          <div>
            <label for="email" class="block text-sm font-light tracking-wide text-gray-700 uppercase mb-3">
              Email Address
            </label>
            <input 
              type="email" 
              id="email" 
              name="email"
              class="w-full px-4 py-3 bg-gray-50 border border-gray-300 text-gray-900 font-light focus:outline-none focus:border-primary-700 transition-colors"
              required
            />
          </div>

          <div>
            <label for="phone" class="block text-sm font-light tracking-wide text-gray-700 uppercase mb-3">
              Phone Number
            </label>
            <input 
              type="tel" 
              id="phone" 
              name="phone"
              class="w-full px-4 py-3 bg-gray-50 border border-gray-300 text-gray-900 font-light focus:outline-none focus:border-primary-700 transition-colors"
            />
          </div>

          <div>
            <label for="aum" class="block text-sm font-light tracking-wide text-gray-700 uppercase mb-3">
              Assets Under Management
            </label>
            <select 
              id="aum" 
              name="aum"
              class="w-full px-4 py-3 bg-gray-50 border border-gray-300 text-gray-900 font-light focus:outline-none focus:border-primary-700 transition-colors"
            >
              <option value="">Please select</option>
              <option value="10-25m">$10M - $25M</option>
              <option value="25-50m">$25M - $50M</option>
              <option value="50-100m">$50M - $100M</option>
              <option value="100m+">$100M+</option>
            </select>
          </div>

          <div>
            <label for="message" class="block text-sm font-light tracking-wide text-gray-700 uppercase mb-3">
              How Can We Assist You?
            </label>
            <textarea 
              id="message" 
              name="message"
              rows="5"
              class="w-full px-4 py-3 bg-gray-50 border border-gray-300 text-gray-900 font-light focus:outline-none focus:border-primary-700 transition-colors resize-none"
            ></textarea>
          </div>

          <button 
            type="submit"
            class="w-full bg-primary-800 hover:bg-primary-700 text-gray-50 px-8 py-4 text-sm font-light tracking-wider transition-all duration-300 border border-primary-700/50"
          >
            SUBMIT INQUIRY
          </button>

          <p class="text-xs font-light text-gray-500 leading-relaxed">
            By submitting this form, you agree to be contacted by Atlas regarding your inquiry. We respect your privacy and will never share your information with third parties.
          </p>
        </form>
      </div>
    </div>
  </div>
</section>
