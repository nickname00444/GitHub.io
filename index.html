const express = require('express');
const mongoose = require('mongoose');
const bodyParser = require('body-parser');
const cors = require('cors');

const app = express();
const PORT = 5000;

// MongoDB 연결
mongoose.connect('mongodb://localhost:27017/driving_simulation', {
  useNewUrlParser: true,
  useUnifiedTopology: true
});

const RecordSchema = new mongoose.Schema({
  date: String,
  time: String,
  distance: String,
  duration: String,
  driver: String,
  team: Number
});

const Record = mongoose.model('Record', RecordSchema);

app.use(cors());
app.use(bodyParser.json());

// 기록 저장 API
app.post('/api/records', async (req, res) => {
  try {
    const newRecord = new Record(req.body);
    await newRecord.save();
    res.status(201).json(newRecord);
  } catch (error) {
    res.status(500).json({ error: '서버 오류' });
  }
});

// 기록 가져오기 API
app.get('/api/records', async (req, res) => {
  try {
    const records = await Record.find();
    res.status(200).json(records);
  } catch (error) {
    res.status(500).json({ error: '서버 오류' });
  }
});

app.listen(PORT, () => {
  console.log(`Server running on port ${PORT}`);
});
