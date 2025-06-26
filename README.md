# keitaui使い方
## インストール
```npm install @keitagames/keitaui```

## 使用例
```javascript
//インストール npm install @keitagames/keitaui
import { default as Input } from '@keitagames/keitaui/src/components/Input'

import { default as Button } from '@keitagames/keitaui/src/components/Button'


function App() {
  
  function a(){

  }
  return (
    <>
      <h1>welcome to project-react</h1>
      <Button label="keitagames" onClick={a}></Button> 
      
      <Input p="keitagames..."></Input>
    </>
  )
}

export default App
```
