<!-- 
const [time, setTime] = useState('08:08:08')
const [rangeTime, setRangeTime] = useState(['08:08:08', '09:09:09'])

<h4>时间点</h4>
<TimePicker
  value={time}
  // disabledTimeRange={['20:10:20-6:30:40', '8:8:8-9:9:9']}  // 禁用时间段
  disabledTimeRange={['17:10:20-23:10:40']}  // 禁用时间段
  changeValue={val => setTime(val)}
  showClearIcon={true}
  placeholder='请选择时间'
/>

<hr/>

<h4>时间范围</h4>
<TimePicker
  showTimeRangePicker={true} // true：表示选择时间范围
  value={rangeTime}
  // disabledTimeRange={['20:10:20-6:30:40', '8:8:8-9:9:9']}  // 禁用时间段
  // disabledTimeRange={['17:10:20-18:10:40']}  // 禁用时间段
  changeValue={val => setRangeTime(val)}
  showClearIcon={true}
  placeholder='请选择时间'
/>

 -->