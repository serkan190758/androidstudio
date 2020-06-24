# androidstudio
Android Studio Projelerim

RequestHandler Kullanım

try {
    JSONObject postDataParams = new JSONObject();
    postDataParams.put("parametre1", "değer1");
    postDataParams.put("parametre2", "değer2");
    new RequestHandler.RequestAsync(getApplicationContext(), "Kendi Siten", postDataParams).execute();
} catch (Exception ex) {
  
}
