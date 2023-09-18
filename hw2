class FooString {
  private:
  char* buf;
  int len;
  public:
  FooString(char* tbuf);
  FooString();
  void show();
  bool compare(FooString str);
};

FooString::FooString(char* tbuf) {
  buf = new char[strlen(tbuf) + 1];
  strcpy(buf, tbuf);
  len = strlen(tbuf);

}
FooString::FooString() {
  buf = nullptr;
  len = 0;
}

void FooString::show() {
  if (buf != nullptr) {
    std::cout « buf;
} 
  else {
    std::cout « “NULL”;
}
}

bool FooString::compare(FooString other) {
  if(buf == other.buf && len == other.len){
    return true;
}
  else {
    return false;
}
}
