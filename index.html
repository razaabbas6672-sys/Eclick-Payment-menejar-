<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>E Click Services - Client Payment Ledger</title>
  <link href="https://fonts.googleapis.com/css2?family=Plus+Jakarta+Sans:wght@400;500;600;700;800&display=swap" rel="stylesheet">
  <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.0/css/all.min.css">
  <style>
    :root {
      --bg-main: #0b0f19;
      --card-bg: rgba(18, 24, 38, 0.95);
      --border: rgba(255, 255, 255, 0.08);
      --primary: #3b82f6;
      --primary-hover: #2563eb;
      --accent: #6366f1;
      --success: #10b981;
      --warning: #f59e0b;
      --danger: #ef4444;
      --text-main: #f8fafc;
      --text-muted: #94a3b8;
    }

    * {
      box-sizing: border-box;
      margin: 0;
      padding: 0;
      font-family: 'Plus Jakarta Sans', sans-serif;
      -webkit-tap-highlight-color: transparent;
    }

    body {
      background: radial-gradient(circle at top right, #1e1b4b, #0b0f19 50%);
      color: var(--text-main);
      min-height: 100vh;
      padding: 16px;
      display: flex;
      justify-content: center;
    }

    .app-container {
      width: 100%;
      max-width: 480px;
      display: flex;
      flex-direction: column;
      gap: 16px;
    }

    header {
      background: var(--card-bg);
      border: 1px solid var(--border);
      border-radius: 20px;
      padding: 20px;
      text-align: center;
      position: relative;
      overflow: hidden;
      box-shadow: 0 10px 25px rgba(0,0,0,0.3);
    }

    header::before {
      content: '';
      position: absolute;
      top: -50%;
      left: -50%;
      width: 200%;
      height: 200%;
      background: radial-gradient(circle, rgba(59, 130, 246, 0.15) 0%, transparent 60%);
      pointer-events: none;
    }

    .brand-title {
      font-size: 1.35rem;
      font-weight: 800;
      letter-spacing: -0.5px;
      background: linear-gradient(135deg, #60a5fa, #a855f7);
      -webkit-background-clip: text;
      -webkit-text-fill-color: transparent;
    }

    .brand-sub {
      font-size: 0.8rem;
      color: var(--text-muted);
      margin-top: 4px;
      font-weight: 500;
    }

    .stats-grid {
      display: grid;
      grid-template-columns: repeat(3, 1fr);
      gap: 10px;
    }

    .stat-box {
      background: var(--card-bg);
      border: 1px solid var(--border);
      border-radius: 16px;
      padding: 14px 10px;
      text-align: center;
      box-shadow: 0 4px 15px rgba(0,0,0,0.2);
    }

    .stat-label {
      font-size: 0.72rem;
      color: var(--text-muted);
      font-weight: 600;
      text-transform: uppercase;
      letter-spacing: 0.5px;
      margin-bottom: 6px;
    }

    .stat-value {
      font-size: 1.05rem;
      font-weight: 800;
    }

    .stat-total { color: #60a5fa; }
    .stat-rec { color: var(--success); }
    .stat-pend { color: var(--danger); }

    .card {
      background: var(--card-bg);
      border: 1px solid var(--border);
      border-radius: 20px;
      padding: 18px;
      box-shadow: 0 8px 20px rgba(0,0,0,0.25);
    }

    .form-group {
      margin-bottom: 12px;
    }

    .form-group label {
      display: block;
      font-size: 0.8rem;
      font-weight: 600;
      margin-bottom: 6px;
      color: var(--text-muted);
    }

    .input-control {
      width: 100%;
      background: rgba(255, 255, 255, 0.04);
      border: 1px solid var(--border);
      border-radius: 12px;
      padding: 12px 14px;
      color: #fff;
      font-size: 0.95rem;
      outline: none;
      transition: all 0.2s ease;
    }

    .input-control:focus {
      border-color: var(--primary);
      background: rgba(59, 130, 246, 0.08);
      box-shadow: 0 0 0 3px rgba(59, 130, 246, 0.2);
    }

    select.input-control option {
      background: #121826;
      color: #fff;
    }

    .btn-submit {
      width: 100%;
      background: linear-gradient(135deg, var(--primary), var(--accent));
      color: #fff;
      border: none;
      border-radius: 12px;
      padding: 14px;
      font-size: 0.95rem;
      font-weight: 700;
      cursor: pointer;
      display: flex;
      align-items: center;
      justify-content: center;
      gap: 8px;
      box-shadow: 0 4px 15px rgba(59, 130, 246, 0.35);
      margin-top: 14px;
      transition: transform 0.1s ease;
    }

    .btn-submit:active {
      transform: scale(0.98);
    }

    .section-header {
      display: flex;
      justify-content: space-between;
      align-items: center;
      margin-bottom: 14px;
    }

    .section-title {
      font-size: 0.95rem;
      font-weight: 700;
    }

    .entry-badge {
      font-size: 0.75rem;
      background: rgba(255, 255, 255, 0.08);
      padding: 3px 10px;
      border-radius: 20px;
      color: var(--text-muted);
    }

    .entry-list {
      display: flex;
      flex-direction: column;
      gap: 12px;
    }

    .entry-item {
      background: rgba(255, 255, 255, 0.03);
      border: 1px solid var(--border);
      border-radius: 16px;
      padding: 14px;
      display: flex;
      justify-content: space-between;
      align-items: center;
      gap: 12px;
    }

    .entry-left {
      flex: 1;
      min-width: 0;
    }

    .client-name {
      font-weight: 700;
      font-size: 0.95rem;
      margin-bottom: 4px;
      white-space: nowrap;
      overflow: hidden;
      text-overflow: ellipsis;
    }

    .entry-meta {
      font-size: 0.75rem;
      color: var(--text-muted);
      display: flex;
      gap: 8px;
      align-items: center;
    }

    .tag {
      padding: 2px 8px;
      border-radius: 6px;
      font-size: 0.7rem;
      font-weight: 700;
    }

    .tag-paid {
      background: rgba(16, 185, 129, 0.15);
      color: var(--success);
    }

    .tag-pending {
      background: rgba(239, 68, 68, 0.15);
      color: var(--danger);
    }

    .entry-right {
      display: flex;
      align-items: center;
      gap: 10px;
    }

    .entry-amount {
      font-size: 1rem;
      font-weight: 800;
      text-align: right;
    }

    .btn-action {
      background: none;
      border: none;
      color: var(--text-muted);
      font-size: 0.95rem;
      cursor: pointer;
      padding: 6px;
      border-radius: 8px;
    }

    .btn-action:hover {
      color: var(--danger);
      background: rgba(239, 68, 68, 0.1);
    }

    .empty-state {
      text-align: center;
      padding: 30px 10px;
      color: var(--text-muted);
      font-size: 0.85rem;
    }
  </style>
</head>
<body>

  <div class="app-container">
    <header>
      <div class="brand-title">E Click Payment Ledger</div>
      <div class="brand-sub">Client Payments & Account Tracker</div>
    </header>

    <div class="stats-grid">
      <div class="stat-box">
        <div class="stat-label">Total</div>
        <div class="stat-value stat-total" id="totalAmount">₹0</div>
      </div>
      <div class="stat-box">
        <div class="stat-label">Received</div>
        <div class="stat-value stat-rec" id="receivedAmount">₹0</div>
      </div>
      <div class="stat-box">
        <div class="stat-label">Pending</div>
        <div class="stat-value stat-pend" id="pendingAmount">₹0</div>
      </div>
    </div>

    <div class="card">
      <div class="form-group">
        <label>Client / Store Name</label>
        <input type="text" id="clientName" class="input-control" placeholder="e.g. Amazon Seller Store">
      </div>
      <div class="form-group">
        <label>Amount (₹)</label>
        <input type="number" id="amount" class="input-control" placeholder="e.g. 5000">
      </div>
      <div class="form-group">
        <label>Payment Status</label>
        <select id="paymentStatus" class="input-control">
          <option value="Paid">Received / Paid</option>
          <option value="Pending">Pending / Due</option>
        </select>
      </div>
      <button class="btn-submit" onclick="addEntry()">
        <i class="fa-solid fa-plus"></i> Add Entry
      </button>
    </div>

    <div class="card">
      <div class="section-header">
        <div class="section-title">Transactions</div>
        <div class="entry-badge" id="entryCount">0 Entries</div>
      </div>
      <div class="entry-list" id="entryList">
        <div class="empty-state">No records added yet.</div>
      </div>
    </div>
  </div>

  <script>
    let entries = JSON.parse(localStorage.getItem('eclick_entries')) || [];

    function renderEntries() {
      const list = document.getElementById('entryList');
      const count = document.getElementById('entryCount');
      let total = 0, received = 0, pending = 0;

      list.innerHTML = '';
      count.innerText = `${entries.length} Entries`;

      if (entries.length === 0) {
        list.innerHTML = '<div class="empty-state">No records added yet.</div>';
      } else {
        entries.forEach((item, index) => {
          const val = parseFloat(item.amount) || 0;
          total += val;
          if (item.status === 'Paid') received += val;
          if (item.status === 'Pending') pending += val;

          const el = document.createElement('div');
          el.className = 'entry-item';
          el.innerHTML = `
            <div class="entry-left">
              <div class="client-name">${item.client}</div>
              <div class="entry-meta">
                <span class="tag ${item.status === 'Paid' ? 'tag-paid' : 'tag-pending'}">${item.status}</span>
                <span>${item.date}</span>
              </div>
            </div>
            <div class="entry-right">
              <div class="entry-amount">₹${val.toLocaleString('en-IN')}</div>
              <button class="btn-action" onclick="deleteEntry(${index})">
                <i class="fa-solid fa-trash-can"></i>
              </button>
            </div>
          `;
          list.appendChild(el);
        });
      }

      document.getElementById('totalAmount').innerText = '₹' + total.toLocaleString('en-IN');
      document.getElementById('receivedAmount').innerText = '₹' + received.toLocaleString('en-IN');
      document.getElementById('pendingAmount').innerText = '₹' + pending.toLocaleString('en-IN');
      localStorage.setItem('eclick_entries', JSON.stringify(entries));
    }

    function addEntry() {
      const nameInput = document.getElementById('clientName');
      const amountInput = document.getElementById('amount');
      const statusInput = document.getElementById('paymentStatus');

      const client = nameInput.value.trim();
      const amount = amountInput.value.trim();
      const status = statusInput.value;

      if (!client || !amount) {
        alert('Please fill both Client Name and Amount.');
        return;
      }

      const today = new Date().toLocaleDateString('en-GB', { day: '2-digit', month: 'short' });
      entries.unshift({ client, amount, status, date: today });

      nameInput.value = '';
      amountInput.value = '';
      renderEntries();
    }

    function deleteEntry(index) {
      entries.splice(index, 1);
      renderEntries();
    }

    renderEntries();
  </script>
</body>
</html>
