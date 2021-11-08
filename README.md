# Audiobook_Speed_Cal
def speed_cal():
    hours = input("enter the number of hours: ")
    minutes = input("enter the number of minutes: ")
    speed = input("enter the playback speed: ")
    H = float(hours) * 60 + float(minutes)
    S = (H / float(speed))
    Listening_time_for_hours = S // 60
    Listening_time_for_minutes = S - Listening_time_for_hours * 60
    L = round(Listening_time_for_minutes)
    print("The Listening Time is %s Hours and %s Minutes" % (Listening_time_for_hours,L))
    
speed_cal()
