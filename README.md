class nodes():
    def __init__(prev,nxt,name,phone_number):
        self.prev=prev
        self.nxt=nxt
        self.name=name
        self.phone_number=phone_numer
    def set_next(nxt):
        self.nxt=nxt
    def set_prev(prev):
        self.prev=prev
    def set_name(name):
        self.name=name
    def set_numer(number):
        self.phone_number=number
    def get_next():
        return self.nxt
    def get_prev():
        return self.prev
class adress_book():
    def __init__(self):
        self.head=node(None,None,None,None)
        self.tail=node(None,None,None,None)
    def total_participants():
        while(self.get_nxt()!=None):
            counter+=1
        return counter
    def add_nodes(self,name,phone_numer):
        if(self.get_nxt()==0):
            self.head.name=name
            self.head.phone_numer=phone_numer
