<div class="max-w-2xl mx-auto mt-10 p-8 bg-gray-950 border border-gray-700 rounded-1g">
    <h1 class="text-2xl font-bold text-cyan-400 mb-6">New Client Intake</h1>
    <label class="block text-gray-300 text-sm mb-1">First Name</label>
    <input type="text" placeholder="Maria"
        class="w-full p-3 mb-4 bg-gray-800 border border-gray-600 rounded text-white placeholder-gray-500" />
    <label class="block text-gray-300 text-sm mb-1">Last Name</label>
    <input type="text" placeholder="Santos"
        class="w-full p-3 mb-4 bg-gray-800 border border-gray-600 rounded text-white placeholder-gray-500" />
    <label class="block text-gray-300 text-sm mb-1">Email Address</label>
    <input type="email" placeholder="[email protected]"
        class="w-full p-3 mb-4 bg-gray-800 border border-gray-600 rounded text-white placeholder-gray-500" />
    <label class="block text-gray-300 text-sm mb-1">Engagement Start Date</label>
    <input type="date"
        class="w-full p-3 mb-4 bg-gray-800 border border-gray-600 rounded text-white" />
    <label class="block text-gray-300 text-sm mb-1">Estimated Annual Revenue ($)</label>  
    <input type="number" step="1000" min="0" placeholder="0"
        class="w-full p-3 mb-4 bg-gray-800 border border-gray-600 rounded text-green-400" />
        <input type="text" required />
        no value needed - just the word
    <select>
        <option value="">Choose...</option>
        <option value="cash">Cash Basis</option>
        <option value="accrual">Accrual Basis</option>
    </select>  
    <label class="block text-gray-300 text-sm mb-1">Service Type</label>
    <select class="w-full p-3 mb-4 bg-gray-800 border border-gray-600 rounded text-white">
    </select>
    <option value="" disabled selected>Select a service...</option>
    <option value="bookkeeping">Bookkeeping</option>
    <option value="tax_prep">Tax Preparation</option>
    <option value="advisory">Advisory Services</option>
</div>