# AWS Cost Analysis Dashboard

A professional Dash dashboard that analyzes AWS costs from December 2024 to May 2025 and projects the financial impact of account deletion decisions.

## 🚀 Features

- **Cost Analysis**: Analyzes costs from Dec 2024 to May 2025
- **Projection Modeling**: Projects annual costs if accounts weren't deleted
- **Savings Calculation**: Shows potential savings from account deletion
- **Professional UI**: Red and white theme perfect for executive presentations
- **Interactive Charts**: Monthly trends, account distribution, and cost projections

## 📊 Dashboard Components

1. **Executive Summary**: Key metrics and overview
2. **Cost Metrics**: Total cost, monthly average, projected annual cost, and savings
3. **Monthly Trend Chart**: Visual representation of cost trends
4. **Account Distribution**: Which accounts contribute most to costs
5. **Projection Analysis**: What costs would be if accounts weren't deleted
6. **Key Insights**: Strategic recommendations

## 🛠️ Setup Instructions

### Local Development

1. **Install Dependencies**:
   ```bash
   pip install -r requirements.txt
   ```

2. **Run the Dashboard**:
   ```bash
   python app.py
   ```

3. **Access Dashboard**:
   Open your browser and go to `http://localhost:8080`

### Replit Deployment

1. **Fork/Clone to Replit**:
   - Create a new Replit project
   - Upload all files or connect via GitHub

2. **Install Dependencies**:
   - Replit will automatically install from `requirements.txt`

3. **Run the App**:
   - Click "Run" in Replit
   - The dashboard will be available at your Replit URL

## 📁 File Structure

```
aws_cost/
├── app.py                 # Main dashboard application
├── requirements.txt       # Python dependencies
├── README.md             # This file
└── final_all_combined_costs.xlsx  # Your cost data
```

## 🔧 Data Requirements

The dashboard expects an Excel file named `final_all_combined_costs.xlsx` with:
- Date column (for time-based analysis)
- Account column (for account-wise analysis)
- Cost column (for financial calculations)

## 🎯 Key Metrics Explained

- **Total Cost**: Sum of all costs from Dec 2024 to May 2025
- **Monthly Average**: Average monthly cost over the 6-month period
- **Projected Annual**: Estimated annual cost if current trend continues
- **Annual Savings**: Estimated savings from account deletion (30% of projected annual)

## 📈 Charts and Visualizations

1. **Monthly Cost Trend**: Bar chart showing cost trends over time
2. **Account Distribution**: Horizontal bar chart showing cost per account
3. **Cost Projection**: Line chart comparing historical vs projected costs

## 🎨 Theme

The dashboard uses a professional red and white theme:
- Primary color: `#dc3545` (Bootstrap danger red)
- Background: `#f8f9fa` (Light gray)
- Cards: White with red accents
- Professional typography and spacing

## 🔄 GitHub Integration

To connect with GitHub:

1. **Initialize Git** (if not already done):
   ```bash
   git init
   git add .
   git commit -m "Initial commit: AWS Cost Analysis Dashboard"
   ```

2. **Create GitHub Repository**:
   - Go to GitHub and create a new repository
   - Follow the instructions to push your code

3. **Connect to Replit**:
   - In Replit, go to "Version Control"
   - Connect to your GitHub repository
   - Pull the latest changes

## 🚀 Deployment Checklist

- [ ] All files uploaded to Replit
- [ ] `requirements.txt` includes all dependencies
- [ ] Excel file (`final_all_combined_costs.xlsx`) is in the project
- [ ] Dashboard runs without errors
- [ ] Charts display correctly
- [ ] Professional presentation ready for executives

## 📞 Support

If you encounter any issues:
1. Check that all dependencies are installed
2. Verify the Excel file format and column names
3. Ensure the file path is correct
4. Check the console for any error messages

## 🎯 Executive Presentation Tips

1. **Focus on Savings**: Emphasize the annual savings potential
2. **Show Trends**: Highlight consistent cost patterns
3. **Risk Mitigation**: Mention security and compliance benefits
4. **Action Items**: Be ready to discuss next steps
5. **Data Accuracy**: Ensure all numbers are current and accurate

---

**Created for AWS Cost Management Analysis**  
*Professional Dashboard for Executive Presentations* 