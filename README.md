# Swift_Weekend
Swift입문 주말반

연락처 : kennysy@naver.com


------------------
# key board 않보이게 하기


    override func touchesBegan(_ touches: Set<UITouch>, with event: UIEvent?) {
        self.view.endEditing(true)
    }
