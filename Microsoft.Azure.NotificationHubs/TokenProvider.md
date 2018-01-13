<Type Name="TokenProvider" FullName="Microsoft.Azure.NotificationHubs.TokenProvider">
  <TypeSignature Language="C#" Value="public abstract class TokenProvider" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract beforefieldinit TokenProvider extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.NotificationHubs.TokenProvider" />
  <TypeSignature Language="VB.NET" Value="Public MustInherit Class TokenProvider" />
  <TypeSignature Language="F#" Value="type TokenProvider = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
    <AssemblyVersion>2.16.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>Stellt einen Sicherheitstokenanbieter mit integrierten Factorymethoden, die einige bekannten Tokenanbieter zurückgeben.</summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="protected TokenProvider (bool cacheTokens, bool supportHttpAuthToken);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig specialname rtspecialname instance void .ctor(bool cacheTokens, bool supportHttpAuthToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.NotificationHubs.TokenProvider.#ctor(System.Boolean,System.Boolean)" />
      <MemberSignature Language="VB.NET" Value="Protected Sub New (cacheTokens As Boolean, supportHttpAuthToken As Boolean)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.NotificationHubs.TokenProvider : bool * bool -&gt; Microsoft.Azure.NotificationHubs.TokenProvider" Usage="new Microsoft.Azure.NotificationHubs.TokenProvider (cacheTokens, supportHttpAuthToken)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="cacheTokens" Type="System.Boolean" />
        <Parameter Name="supportHttpAuthToken" Type="System.Boolean" />
      </Parameters>
      <Docs>
        <param name="cacheTokens">"true", wenn neue Sicherheitstokens zwischengespeichert sind; andernfalls "false".</param>
        <param name="supportHttpAuthToken">"true", wenn webtoken von diesem Anbieter unterstützt wird; andernfalls "false".</param>
        <summary>Initialisiert eine neue Instanz der <see cref="T:Microsoft.Azure.NotificationHubs.TokenProvider" />-Klasse.</summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="protected TokenProvider (bool cacheTokens, bool supportHttpAuthToken, Microsoft.Azure.NotificationHubs.TokenScope tokenScope);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig specialname rtspecialname instance void .ctor(bool cacheTokens, bool supportHttpAuthToken, valuetype Microsoft.Azure.NotificationHubs.TokenScope tokenScope) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.NotificationHubs.TokenProvider.#ctor(System.Boolean,System.Boolean,Microsoft.Azure.NotificationHubs.TokenScope)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.NotificationHubs.TokenProvider : bool * bool * Microsoft.Azure.NotificationHubs.TokenScope -&gt; Microsoft.Azure.NotificationHubs.TokenProvider" Usage="new Microsoft.Azure.NotificationHubs.TokenProvider (cacheTokens, supportHttpAuthToken, tokenScope)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="cacheTokens" Type="System.Boolean" />
        <Parameter Name="supportHttpAuthToken" Type="System.Boolean" />
        <Parameter Name="tokenScope" Type="Microsoft.Azure.NotificationHubs.TokenScope" />
      </Parameters>
      <Docs>
        <param name="cacheTokens">"true", wenn neue Sicherheitstokens zwischengespeichert sind; andernfalls "false".</param>
        <param name="supportHttpAuthToken">"true", wenn webtoken von diesem Anbieter unterstützt wird; andernfalls "false".</param>
        <param name="tokenScope">Der token Bereich, der dem Anbieter zugeordnet ist.</param>
        <summary>Initialisiert eine neue Instanz der <see cref="T:Microsoft.Azure.NotificationHubs.TokenProvider" />-Klasse.</summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="protected TokenProvider (bool cacheTokens, bool supportHttpAuthToken, int cacheSize, Microsoft.Azure.NotificationHubs.TokenScope tokenScope);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig specialname rtspecialname instance void .ctor(bool cacheTokens, bool supportHttpAuthToken, int32 cacheSize, valuetype Microsoft.Azure.NotificationHubs.TokenScope tokenScope) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.NotificationHubs.TokenProvider.#ctor(System.Boolean,System.Boolean,System.Int32,Microsoft.Azure.NotificationHubs.TokenScope)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.NotificationHubs.TokenProvider : bool * bool * int * Microsoft.Azure.NotificationHubs.TokenScope -&gt; Microsoft.Azure.NotificationHubs.TokenProvider" Usage="new Microsoft.Azure.NotificationHubs.TokenProvider (cacheTokens, supportHttpAuthToken, cacheSize, tokenScope)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="cacheTokens" Type="System.Boolean" />
        <Parameter Name="supportHttpAuthToken" Type="System.Boolean" />
        <Parameter Name="cacheSize" Type="System.Int32" />
        <Parameter Name="tokenScope" Type="Microsoft.Azure.NotificationHubs.TokenScope" />
      </Parameters>
      <Docs>
        <param name="cacheTokens">"true", wenn neue Sicherheitstokens zwischengespeichert sind; andernfalls "false".</param>
        <param name="supportHttpAuthToken">"true", wenn webtoken von diesem Anbieter unterstützt wird; andernfalls "false".</param>
        <param name="cacheSize">Die Größe des Caches.</param>
        <param name="tokenScope">Der token Bereich, der dem Anbieter zugeordnet ist.</param>
        <summary>Initialisiert eine neue Instanz der <see cref="T:Microsoft.Azure.NotificationHubs.TokenProvider" />-Klasse.</summary>
        <remarks>To be added.</remarks>
        <exception cref="T:System.ArgumentOutOfRangeException">cacheSize</exception>
      </Docs>
    </Member>
    <Member MemberName="BeginGetToken">
      <MemberSignature Language="C#" Value="public IAsyncResult BeginGetToken (string appliesTo, string action, bool bypassCache, TimeSpan timeout, AsyncCallback callback, object state);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.IAsyncResult BeginGetToken(string appliesTo, string action, bool bypassCache, valuetype System.TimeSpan timeout, class System.AsyncCallback callback, object state) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.NotificationHubs.TokenProvider.BeginGetToken(System.String,System.String,System.Boolean,System.TimeSpan,System.AsyncCallback,System.Object)" />
      <MemberSignature Language="VB.NET" Value="Public Function BeginGetToken (appliesTo As String, action As String, bypassCache As Boolean, timeout As TimeSpan, callback As AsyncCallback, state As Object) As IAsyncResult" />
      <MemberSignature Language="F#" Value="member this.BeginGetToken : string * string * bool * TimeSpan * AsyncCallback * obj -&gt; IAsyncResult" Usage="tokenProvider.BeginGetToken (appliesTo, action, bypassCache, timeout, callback, state)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.IAsyncResult</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="appliesTo" Type="System.String" />
        <Parameter Name="action" Type="System.String" />
        <Parameter Name="bypassCache" Type="System.Boolean" />
        <Parameter Name="timeout" Type="System.TimeSpan" />
        <Parameter Name="callback" Type="System.AsyncCallback" />
        <Parameter Name="state" Type="System.Object" />
      </Parameters>
      <Docs>
        <param name="appliesTo">Der URI, der das Zugriffstoken gilt.</param>
        <param name="action">Die anforderungsaktion.</param>
        <param name="bypassCache">"true", um vorhandene Tokeninformationen im Cache zu ignorieren; "false", der token Informationen im Cache zu verwenden.</param>
        <param name="timeout">Die Zeitspanne, die den Timeoutwert für die Nachricht gibt an, die Ruft das Sicherheitstoken ab.</param>
        <param name="callback">Ein <see cref="T:System.AsyncCallback" />-Delegat, der auf die Methode verweist, die bei Abschluss des Vorgangs aufgerufen werden soll.</param>
        <param name="state">Ein benutzerdefiniertes Objekt, das Statusinformationen über den asynchronen Vorgang enthält. </param>
        <summary>Startet einen asynchronen Vorgang, um ein Sicherheitstoken abzurufen.</summary>
        <returns>Ein <see cref="T:System.IAsyncResult" /> Objekt, das den asynchronen Vorgang zum Abrufen eines Tokens verweist.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginGetWebToken">
      <MemberSignature Language="C#" Value="public IAsyncResult BeginGetWebToken (string appliesTo, string action, bool bypassCache, TimeSpan timeout, AsyncCallback callback, object state);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.IAsyncResult BeginGetWebToken(string appliesTo, string action, bool bypassCache, valuetype System.TimeSpan timeout, class System.AsyncCallback callback, object state) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.NotificationHubs.TokenProvider.BeginGetWebToken(System.String,System.String,System.Boolean,System.TimeSpan,System.AsyncCallback,System.Object)" />
      <MemberSignature Language="VB.NET" Value="Public Function BeginGetWebToken (appliesTo As String, action As String, bypassCache As Boolean, timeout As TimeSpan, callback As AsyncCallback, state As Object) As IAsyncResult" />
      <MemberSignature Language="F#" Value="member this.BeginGetWebToken : string * string * bool * TimeSpan * AsyncCallback * obj -&gt; IAsyncResult" Usage="tokenProvider.BeginGetWebToken (appliesTo, action, bypassCache, timeout, callback, state)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.IAsyncResult</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="appliesTo" Type="System.String" />
        <Parameter Name="action" Type="System.String" />
        <Parameter Name="bypassCache" Type="System.Boolean" />
        <Parameter Name="timeout" Type="System.TimeSpan" />
        <Parameter Name="callback" Type="System.AsyncCallback" />
        <Parameter Name="state" Type="System.Object" />
      </Parameters>
      <Docs>
        <param name="appliesTo">Der URI, der das Token gilt.</param>
        <param name="action">Die anforderungsaktion.</param>
        <param name="bypassCache">"true", um vorhandene Tokeninformationen im Cache zu ignorieren; "false", der token Informationen im Cache zu verwenden.</param>
        <param name="timeout">Die Zeitspanne, die den Timeoutwert für die Nachricht gibt an, die Ruft das Sicherheitstoken ab.</param>
        <param name="callback">Ein <see cref="T:System.AsyncCallback" />-Delegat, der auf die Methode verweist, die bei Abschluss des Vorgangs aufgerufen werden soll.</param>
        <param name="state">Ein benutzerdefiniertes Objekt, das Statusinformationen über den asynchronen Vorgang enthält. </param>
        <summary>Startet einen asynchronen Vorgang zum Abrufen einer webtoken.</summary>
        <returns>Ein <see cref="T:System.IAsyncResult" /> Objekt, das den asynchronen Vorgang zum Abrufen einer webtoken verweist.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BuildKey">
      <MemberSignature Language="C#" Value="protected virtual Microsoft.Azure.NotificationHubs.TokenProvider.Key BuildKey (string appliesTo, string action);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig newslot virtual instance class Microsoft.Azure.NotificationHubs.TokenProvider/Key BuildKey(string appliesTo, string action) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.NotificationHubs.TokenProvider.BuildKey(System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Protected Overridable Function BuildKey (appliesTo As String, action As String) As TokenProvider.Key" />
      <MemberSignature Language="F#" Value="abstract member BuildKey : string * string -&gt; Microsoft.Azure.NotificationHubs.TokenProvider.Key&#xA;override this.BuildKey : string * string -&gt; Microsoft.Azure.NotificationHubs.TokenProvider.Key" Usage="tokenProvider.BuildKey (appliesTo, action)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.NotificationHubs.TokenProvider+Key</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="appliesTo" Type="System.String" />
        <Parameter Name="action" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="appliesTo">Der URI, der das Zugriffstoken gilt.</param>
        <param name="action">Die anforderungsaktion.</param>
        <summary>Generiert einen Schlüssel für den Anbieter von Sicherheitstoken.</summary>
        <returns>Ein generierter Schlüssel für den Anbieter von Sicherheitstoken.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CacheSize">
      <MemberSignature Language="C#" Value="public int CacheSize { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int32 CacheSize" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.NotificationHubs.TokenProvider.CacheSize" />
      <MemberSignature Language="VB.NET" Value="Public Property CacheSize As Integer" />
      <MemberSignature Language="F#" Value="member this.CacheSize : int with get, set" Usage="Microsoft.Azure.NotificationHubs.TokenProvider.CacheSize" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Int32</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>Ruft ab oder legt die Größe des Caches.</summary>
        <value>Die Größe des Caches.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CacheTokens">
      <MemberSignature Language="C#" Value="public bool CacheTokens { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance bool CacheTokens" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.NotificationHubs.TokenProvider.CacheTokens" />
      <MemberSignature Language="VB.NET" Value="Public Property CacheTokens As Boolean" />
      <MemberSignature Language="F#" Value="member this.CacheTokens : bool with get, set" Usage="Microsoft.Azure.NotificationHubs.TokenProvider.CacheTokens" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>Ruft ab oder legt einen Wert, der angibt, ob neue Sicherheitstokens zwischengespeichert werden.</summary>
        <value>"true", wenn neue Sicherheitstokens zwischengespeichert sind; andernfalls "false".</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Clear">
      <MemberSignature Language="C#" Value="public void Clear ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance void Clear() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.NotificationHubs.TokenProvider.Clear" />
      <MemberSignature Language="VB.NET" Value="Public Sub Clear ()" />
      <MemberSignature Language="F#" Value="member this.Clear : unit -&gt; unit" Usage="tokenProvider.Clear " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>Löscht den Tokenanbieter.</summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateOAuthTokenProvider">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.NotificationHubs.TokenProvider CreateOAuthTokenProvider (System.Collections.Generic.IEnumerable&lt;Uri&gt; stsUris, System.Net.NetworkCredential credential);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.NotificationHubs.TokenProvider CreateOAuthTokenProvider(class System.Collections.Generic.IEnumerable`1&lt;class System.Uri&gt; stsUris, class System.Net.NetworkCredential credential) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.NotificationHubs.TokenProvider.CreateOAuthTokenProvider(System.Collections.Generic.IEnumerable{System.Uri},System.Net.NetworkCredential)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function CreateOAuthTokenProvider (stsUris As IEnumerable(Of Uri), credential As NetworkCredential) As TokenProvider" />
      <MemberSignature Language="F#" Value="static member CreateOAuthTokenProvider : seq&lt;Uri&gt; * System.Net.NetworkCredential -&gt; Microsoft.Azure.NotificationHubs.TokenProvider" Usage="Microsoft.Azure.NotificationHubs.TokenProvider.CreateOAuthTokenProvider (stsUris, credential)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.NotificationHubs.TokenProvider</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="stsUris" Type="System.Collections.Generic.IEnumerable&lt;System.Uri&gt;" />
        <Parameter Name="credential" Type="System.Net.NetworkCredential" />
      </Parameters>
      <Docs>
        <param name="stsUris">Die URIs der Sicherheitstokendienst (STS).</param>
        <param name="credential">Die Anmeldeinformationen des Benutzers.</param>
        <summary>Erstellt ein Tokenanbieter OAuth (offenen Standard zur Autorisierung).</summary>
        <returns>Die <see cref="T:Microsoft.Azure.NotificationHubs.TokenProvider" /> für die Rückgabe der OAuth-Token.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateSharedAccessSignatureTokenProvider">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.NotificationHubs.TokenProvider CreateSharedAccessSignatureTokenProvider (string sharedAccessSignature);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.NotificationHubs.TokenProvider CreateSharedAccessSignatureTokenProvider(string sharedAccessSignature) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.NotificationHubs.TokenProvider.CreateSharedAccessSignatureTokenProvider(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function CreateSharedAccessSignatureTokenProvider (sharedAccessSignature As String) As TokenProvider" />
      <MemberSignature Language="F#" Value="static member CreateSharedAccessSignatureTokenProvider : string -&gt; Microsoft.Azure.NotificationHubs.TokenProvider" Usage="Microsoft.Azure.NotificationHubs.TokenProvider.CreateSharedAccessSignatureTokenProvider sharedAccessSignature" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.NotificationHubs.TokenProvider</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="sharedAccessSignature" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="sharedAccessSignature">Die SAS</param>
        <summary>
            Erstellen Sie einen TokenProvider dar, die basierend auf einer SharedAccessSignature.
            </summary>
        <returns>Einen TokenProvider dar, die mit der freigegebenen zugriffssignatur initialisiert</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateSharedAccessSignatureTokenProvider">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.NotificationHubs.TokenProvider CreateSharedAccessSignatureTokenProvider (string keyName, string sharedAccessKey);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.NotificationHubs.TokenProvider CreateSharedAccessSignatureTokenProvider(string keyName, string sharedAccessKey) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.NotificationHubs.TokenProvider.CreateSharedAccessSignatureTokenProvider(System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function CreateSharedAccessSignatureTokenProvider (keyName As String, sharedAccessKey As String) As TokenProvider" />
      <MemberSignature Language="F#" Value="static member CreateSharedAccessSignatureTokenProvider : string * string -&gt; Microsoft.Azure.NotificationHubs.TokenProvider" Usage="Microsoft.Azure.NotificationHubs.TokenProvider.CreateSharedAccessSignatureTokenProvider (keyName, sharedAccessKey)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.NotificationHubs.TokenProvider</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="keyName" Type="System.String" />
        <Parameter Name="sharedAccessKey" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="keyName">Der Schlüsselname.</param>
        <param name="sharedAccessKey">Der SAS-Schlüssel.</param>
        <summary>Erstellt eine URL, die Zugriff auf Anbieter von Sicherheitstoken mit dem angegebenen Schlüsselnamen und SAS-Schlüssel.</summary>
        <returns>Die erstellte URL, die Zugriff auf Anbieter von Sicherheitstoken.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateSharedAccessSignatureTokenProvider">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.NotificationHubs.TokenProvider CreateSharedAccessSignatureTokenProvider (string keyName, string sharedAccessKey, Microsoft.Azure.NotificationHubs.TokenScope tokenScope);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.NotificationHubs.TokenProvider CreateSharedAccessSignatureTokenProvider(string keyName, string sharedAccessKey, valuetype Microsoft.Azure.NotificationHubs.TokenScope tokenScope) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.NotificationHubs.TokenProvider.CreateSharedAccessSignatureTokenProvider(System.String,System.String,Microsoft.Azure.NotificationHubs.TokenScope)" />
      <MemberSignature Language="F#" Value="static member CreateSharedAccessSignatureTokenProvider : string * string * Microsoft.Azure.NotificationHubs.TokenScope -&gt; Microsoft.Azure.NotificationHubs.TokenProvider" Usage="Microsoft.Azure.NotificationHubs.TokenProvider.CreateSharedAccessSignatureTokenProvider (keyName, sharedAccessKey, tokenScope)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.NotificationHubs.TokenProvider</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="keyName" Type="System.String" />
        <Parameter Name="sharedAccessKey" Type="System.String" />
        <Parameter Name="tokenScope" Type="Microsoft.Azure.NotificationHubs.TokenScope" />
      </Parameters>
      <Docs>
        <param name="keyName">Der Schlüsselname.</param>
        <param name="sharedAccessKey">Der SAS-Schlüssel.</param>
        <param name="tokenScope">Der token Bereich, der dem Anbieter zugeordnet ist.</param>
        <summary>Erstellt eine URL, die Zugriff auf Anbieter von Sicherheitstoken mit dem angegebenen Schlüsselnamen, SAS-Schlüssel und token-Bereich.</summary>
        <returns>Die erstellte URL, die Zugriff auf Anbieter von Sicherheitstoken.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateSharedAccessSignatureTokenProvider">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.NotificationHubs.TokenProvider CreateSharedAccessSignatureTokenProvider (string keyName, string sharedAccessKey, TimeSpan tokenTimeToLive);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.NotificationHubs.TokenProvider CreateSharedAccessSignatureTokenProvider(string keyName, string sharedAccessKey, valuetype System.TimeSpan tokenTimeToLive) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.NotificationHubs.TokenProvider.CreateSharedAccessSignatureTokenProvider(System.String,System.String,System.TimeSpan)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function CreateSharedAccessSignatureTokenProvider (keyName As String, sharedAccessKey As String, tokenTimeToLive As TimeSpan) As TokenProvider" />
      <MemberSignature Language="F#" Value="static member CreateSharedAccessSignatureTokenProvider : string * string * TimeSpan -&gt; Microsoft.Azure.NotificationHubs.TokenProvider" Usage="Microsoft.Azure.NotificationHubs.TokenProvider.CreateSharedAccessSignatureTokenProvider (keyName, sharedAccessKey, tokenTimeToLive)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.NotificationHubs.TokenProvider</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="keyName" Type="System.String" />
        <Parameter Name="sharedAccessKey" Type="System.String" />
        <Parameter Name="tokenTimeToLive" Type="System.TimeSpan" />
      </Parameters>
      <Docs>
        <param name="keyName">Der Schlüsselname.</param>
        <param name="sharedAccessKey">Der SAS-Schlüssel.</param>
        <param name="tokenTimeToLive">Die Zeit für die der Vorgang gültig bleibt.</param>
        <summary>Erstellt eine URL, die Zugriff auf Anbieter von Sicherheitstoken mit dem angegebenen Schlüsselnamen, SAS-Schlüssel und token Zeit Gültigkeitsdauer.</summary>
        <returns>Die erstellte URL, die Zugriff auf Anbieter von Sicherheitstoken.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateSharedAccessSignatureTokenProvider">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.NotificationHubs.TokenProvider CreateSharedAccessSignatureTokenProvider (string keyName, string sharedAccessKey, TimeSpan tokenTimeToLive, Microsoft.Azure.NotificationHubs.TokenScope tokenScope);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.NotificationHubs.TokenProvider CreateSharedAccessSignatureTokenProvider(string keyName, string sharedAccessKey, valuetype System.TimeSpan tokenTimeToLive, valuetype Microsoft.Azure.NotificationHubs.TokenScope tokenScope) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.NotificationHubs.TokenProvider.CreateSharedAccessSignatureTokenProvider(System.String,System.String,System.TimeSpan,Microsoft.Azure.NotificationHubs.TokenScope)" />
      <MemberSignature Language="F#" Value="static member CreateSharedAccessSignatureTokenProvider : string * string * TimeSpan * Microsoft.Azure.NotificationHubs.TokenScope -&gt; Microsoft.Azure.NotificationHubs.TokenProvider" Usage="Microsoft.Azure.NotificationHubs.TokenProvider.CreateSharedAccessSignatureTokenProvider (keyName, sharedAccessKey, tokenTimeToLive, tokenScope)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.NotificationHubs.TokenProvider</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="keyName" Type="System.String" />
        <Parameter Name="sharedAccessKey" Type="System.String" />
        <Parameter Name="tokenTimeToLive" Type="System.TimeSpan" />
        <Parameter Name="tokenScope" Type="Microsoft.Azure.NotificationHubs.TokenScope" />
      </Parameters>
      <Docs>
        <param name="keyName">Der Schlüsselname.</param>
        <param name="sharedAccessKey">Der SAS-Schlüssel.</param>
        <param name="tokenTimeToLive">Die Zeit für die der Vorgang gültig bleibt.</param>
        <param name="tokenScope">Der token Bereich, der dem Anbieter zugeordnet ist.</param>
        <summary>Erstellt eine URL, die Zugriff auf Anbieter von Sicherheitstoken.</summary>
        <returns>Die erstellte URL, die Zugriff auf Anbieter von Sicherheitstoken.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateSharedSecretTokenProvider">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.NotificationHubs.TokenProvider CreateSharedSecretTokenProvider (string issuerName, byte[] issuerSecret);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.NotificationHubs.TokenProvider CreateSharedSecretTokenProvider(string issuerName, unsigned int8[] issuerSecret) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.NotificationHubs.TokenProvider.CreateSharedSecretTokenProvider(System.String,System.Byte[])" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function CreateSharedSecretTokenProvider (issuerName As String, issuerSecret As Byte()) As TokenProvider" />
      <MemberSignature Language="F#" Value="static member CreateSharedSecretTokenProvider : string * byte[] -&gt; Microsoft.Azure.NotificationHubs.TokenProvider" Usage="Microsoft.Azure.NotificationHubs.TokenProvider.CreateSharedSecretTokenProvider (issuerName, issuerSecret)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.NotificationHubs.TokenProvider</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="issuerName" Type="System.String" />
        <Parameter Name="issuerSecret" Type="System.Byte[]" />
      </Parameters>
      <Docs>
        <param name="issuerName">Der Ausstellername.</param>
        <param name="issuerSecret">Der geheime Ausstellerschlüssel.</param>
        <summary>Erstellt einen freigegebenen geheimen Tokenanbieter.</summary>
        <returns>Die <see cref="T:Microsoft.Azure.NotificationHubs.TokenProvider" /> für die Rückgabe gemeinsamen geheimen Tokens.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateSharedSecretTokenProvider">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.NotificationHubs.TokenProvider CreateSharedSecretTokenProvider (string issuerName, string issuerSecret);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.NotificationHubs.TokenProvider CreateSharedSecretTokenProvider(string issuerName, string issuerSecret) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.NotificationHubs.TokenProvider.CreateSharedSecretTokenProvider(System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function CreateSharedSecretTokenProvider (issuerName As String, issuerSecret As String) As TokenProvider" />
      <MemberSignature Language="F#" Value="static member CreateSharedSecretTokenProvider : string * string -&gt; Microsoft.Azure.NotificationHubs.TokenProvider" Usage="Microsoft.Azure.NotificationHubs.TokenProvider.CreateSharedSecretTokenProvider (issuerName, issuerSecret)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.NotificationHubs.TokenProvider</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="issuerName" Type="System.String" />
        <Parameter Name="issuerSecret" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="issuerName">Der Ausstellername.</param>
        <param name="issuerSecret">Der geheime Ausstellerschlüssel.</param>
        <summary>Erstellt einen freigegebenen geheimen Tokenanbieter.</summary>
        <returns>Die <see cref="T:Microsoft.Azure.NotificationHubs.TokenProvider" /> für die Rückgabe gemeinsamen geheimen Tokens.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateSharedSecretTokenProvider">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.NotificationHubs.TokenProvider CreateSharedSecretTokenProvider (string issuerName, byte[] issuerSecret, Microsoft.Azure.NotificationHubs.TokenScope tokenScope);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.NotificationHubs.TokenProvider CreateSharedSecretTokenProvider(string issuerName, unsigned int8[] issuerSecret, valuetype Microsoft.Azure.NotificationHubs.TokenScope tokenScope) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.NotificationHubs.TokenProvider.CreateSharedSecretTokenProvider(System.String,System.Byte[],Microsoft.Azure.NotificationHubs.TokenScope)" />
      <MemberSignature Language="F#" Value="static member CreateSharedSecretTokenProvider : string * byte[] * Microsoft.Azure.NotificationHubs.TokenScope -&gt; Microsoft.Azure.NotificationHubs.TokenProvider" Usage="Microsoft.Azure.NotificationHubs.TokenProvider.CreateSharedSecretTokenProvider (issuerName, issuerSecret, tokenScope)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.NotificationHubs.TokenProvider</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="issuerName" Type="System.String" />
        <Parameter Name="issuerSecret" Type="System.Byte[]" />
        <Parameter Name="tokenScope" Type="Microsoft.Azure.NotificationHubs.TokenScope" />
      </Parameters>
      <Docs>
        <param name="issuerName">Der Name des Ausstellers.</param>
        <param name="issuerSecret">Der Satz von geheimen Schlüssel des Ausstellers.</param>
        <param name="tokenScope">Der token Bereich, der dem Anbieter zugeordnet ist.</param>
        <summary>Erstellt einen freigegebenen geheimen Tokenanbieter.</summary>
        <returns>Der Tokenanbieter erstellt.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateSharedSecretTokenProvider">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.NotificationHubs.TokenProvider CreateSharedSecretTokenProvider (string issuerName, byte[] issuerSecret, Uri stsUri);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.NotificationHubs.TokenProvider CreateSharedSecretTokenProvider(string issuerName, unsigned int8[] issuerSecret, class System.Uri stsUri) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.NotificationHubs.TokenProvider.CreateSharedSecretTokenProvider(System.String,System.Byte[],System.Uri)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function CreateSharedSecretTokenProvider (issuerName As String, issuerSecret As Byte(), stsUri As Uri) As TokenProvider" />
      <MemberSignature Language="F#" Value="static member CreateSharedSecretTokenProvider : string * byte[] * Uri -&gt; Microsoft.Azure.NotificationHubs.TokenProvider" Usage="Microsoft.Azure.NotificationHubs.TokenProvider.CreateSharedSecretTokenProvider (issuerName, issuerSecret, stsUri)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.NotificationHubs.TokenProvider</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="issuerName" Type="System.String" />
        <Parameter Name="issuerSecret" Type="System.Byte[]" />
        <Parameter Name="stsUri" Type="System.Uri" />
      </Parameters>
      <Docs>
        <param name="issuerName">Der Ausstellername.</param>
        <param name="issuerSecret">Der Satz von geheimen Schlüssel des Ausstellers.</param>
        <param name="stsUri">Der URI der Sicherheitstokendienst (STS).</param>
        <summary>Erstellt einen freigegebenen geheimen Tokenanbieter.</summary>
        <returns>Die <see cref="T:Microsoft.Azure.NotificationHubs.TokenProvider" /> für die Rückgabe gemeinsamen geheimen Tokens.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateSharedSecretTokenProvider">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.NotificationHubs.TokenProvider CreateSharedSecretTokenProvider (string issuerName, string issuerSecret, Microsoft.Azure.NotificationHubs.TokenScope tokenScope);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.NotificationHubs.TokenProvider CreateSharedSecretTokenProvider(string issuerName, string issuerSecret, valuetype Microsoft.Azure.NotificationHubs.TokenScope tokenScope) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.NotificationHubs.TokenProvider.CreateSharedSecretTokenProvider(System.String,System.String,Microsoft.Azure.NotificationHubs.TokenScope)" />
      <MemberSignature Language="F#" Value="static member CreateSharedSecretTokenProvider : string * string * Microsoft.Azure.NotificationHubs.TokenScope -&gt; Microsoft.Azure.NotificationHubs.TokenProvider" Usage="Microsoft.Azure.NotificationHubs.TokenProvider.CreateSharedSecretTokenProvider (issuerName, issuerSecret, tokenScope)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.NotificationHubs.TokenProvider</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="issuerName" Type="System.String" />
        <Parameter Name="issuerSecret" Type="System.String" />
        <Parameter Name="tokenScope" Type="Microsoft.Azure.NotificationHubs.TokenScope" />
      </Parameters>
      <Docs>
        <param name="issuerName">Der Ausstellername.</param>
        <param name="issuerSecret">Der geheime Ausstellerschlüssel.</param>
        <param name="tokenScope">Der token Bereich, der dem Anbieter zugeordnet ist.</param>
        <summary>Erstellt einen freigegebenen geheimen Tokenanbieter.</summary>
        <returns>Der Tokenanbieter erstellt.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateSharedSecretTokenProvider">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.NotificationHubs.TokenProvider CreateSharedSecretTokenProvider (string issuerName, string issuerSecret, Uri stsUri);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.NotificationHubs.TokenProvider CreateSharedSecretTokenProvider(string issuerName, string issuerSecret, class System.Uri stsUri) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.NotificationHubs.TokenProvider.CreateSharedSecretTokenProvider(System.String,System.String,System.Uri)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function CreateSharedSecretTokenProvider (issuerName As String, issuerSecret As String, stsUri As Uri) As TokenProvider" />
      <MemberSignature Language="F#" Value="static member CreateSharedSecretTokenProvider : string * string * Uri -&gt; Microsoft.Azure.NotificationHubs.TokenProvider" Usage="Microsoft.Azure.NotificationHubs.TokenProvider.CreateSharedSecretTokenProvider (issuerName, issuerSecret, stsUri)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.NotificationHubs.TokenProvider</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="issuerName" Type="System.String" />
        <Parameter Name="issuerSecret" Type="System.String" />
        <Parameter Name="stsUri" Type="System.Uri" />
      </Parameters>
      <Docs>
        <param name="issuerName">Der Ausstellername.</param>
        <param name="issuerSecret">Der geheime Ausstellerschlüssel.</param>
        <param name="stsUri">Der URI der Sicherheitstokendienst (STS).</param>
        <summary>Erstellt einen freigegebenen geheimen Tokenanbieter.</summary>
        <returns>Die <see cref="T:Microsoft.Azure.NotificationHubs.TokenProvider" /> für die Rückgabe gemeinsamen geheimen Tokens.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateSharedSecretTokenProvider">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.NotificationHubs.TokenProvider CreateSharedSecretTokenProvider (string issuerName, byte[] issuerSecret, Uri stsUri, Microsoft.Azure.NotificationHubs.TokenScope tokenScope);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.NotificationHubs.TokenProvider CreateSharedSecretTokenProvider(string issuerName, unsigned int8[] issuerSecret, class System.Uri stsUri, valuetype Microsoft.Azure.NotificationHubs.TokenScope tokenScope) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.NotificationHubs.TokenProvider.CreateSharedSecretTokenProvider(System.String,System.Byte[],System.Uri,Microsoft.Azure.NotificationHubs.TokenScope)" />
      <MemberSignature Language="F#" Value="static member CreateSharedSecretTokenProvider : string * byte[] * Uri * Microsoft.Azure.NotificationHubs.TokenScope -&gt; Microsoft.Azure.NotificationHubs.TokenProvider" Usage="Microsoft.Azure.NotificationHubs.TokenProvider.CreateSharedSecretTokenProvider (issuerName, issuerSecret, stsUri, tokenScope)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.NotificationHubs.TokenProvider</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="issuerName" Type="System.String" />
        <Parameter Name="issuerSecret" Type="System.Byte[]" />
        <Parameter Name="stsUri" Type="System.Uri" />
        <Parameter Name="tokenScope" Type="Microsoft.Azure.NotificationHubs.TokenScope" />
      </Parameters>
      <Docs>
        <param name="issuerName">Der Ausstellername.</param>
        <param name="issuerSecret">Der Satz von geheimen Schlüssel des Ausstellers.</param>
        <param name="stsUri">Der STS Endpunkt-Uri.</param>
        <param name="tokenScope">Der token Bereich, der dem Anbieter zugeordnet ist.</param>
        <summary>Erstellt einen freigegebenen geheimen Tokenanbieter.</summary>
        <returns>Der Tokenanbieter erstellt.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateSharedSecretTokenProvider">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.NotificationHubs.TokenProvider CreateSharedSecretTokenProvider (string issuerName, string issuerSecret, Uri stsUri, Microsoft.Azure.NotificationHubs.TokenScope tokenScope);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.NotificationHubs.TokenProvider CreateSharedSecretTokenProvider(string issuerName, string issuerSecret, class System.Uri stsUri, valuetype Microsoft.Azure.NotificationHubs.TokenScope tokenScope) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.NotificationHubs.TokenProvider.CreateSharedSecretTokenProvider(System.String,System.String,System.Uri,Microsoft.Azure.NotificationHubs.TokenScope)" />
      <MemberSignature Language="F#" Value="static member CreateSharedSecretTokenProvider : string * string * Uri * Microsoft.Azure.NotificationHubs.TokenScope -&gt; Microsoft.Azure.NotificationHubs.TokenProvider" Usage="Microsoft.Azure.NotificationHubs.TokenProvider.CreateSharedSecretTokenProvider (issuerName, issuerSecret, stsUri, tokenScope)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.NotificationHubs.TokenProvider</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="issuerName" Type="System.String" />
        <Parameter Name="issuerSecret" Type="System.String" />
        <Parameter Name="stsUri" Type="System.Uri" />
        <Parameter Name="tokenScope" Type="Microsoft.Azure.NotificationHubs.TokenScope" />
      </Parameters>
      <Docs>
        <param name="issuerName">Der Ausstellername.</param>
        <param name="issuerSecret">Der geheime Ausstellerschlüssel.</param>
        <param name="stsUri">Der URI der Sicherheitstokendienst (STS).</param>
        <param name="tokenScope">Der token Bereich, der dem Anbieter zugeordnet ist.</param>
        <summary>Erstellt einen freigegebenen geheimen Tokenanbieter.</summary>
        <returns>Der Tokenanbieter erstellt.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateSimpleWebTokenProvider">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.NotificationHubs.TokenProvider CreateSimpleWebTokenProvider (string token);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.NotificationHubs.TokenProvider CreateSimpleWebTokenProvider(string token) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.NotificationHubs.TokenProvider.CreateSimpleWebTokenProvider(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function CreateSimpleWebTokenProvider (token As String) As TokenProvider" />
      <MemberSignature Language="F#" Value="static member CreateSimpleWebTokenProvider : string -&gt; Microsoft.Azure.NotificationHubs.TokenProvider" Usage="Microsoft.Azure.NotificationHubs.TokenProvider.CreateSimpleWebTokenProvider token" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.NotificationHubs.TokenProvider</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="token" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="token">Die Zeichenfolge, die das simple webtoken darstellt.</param>
        <summary>Erstellt einen einfache Web-Tokenanbieter.</summary>
        <returns>Die <see cref="T:Microsoft.Azure.NotificationHubs.TokenProvider" /> für die Rückgabe von einfachen webtoken.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateSimpleWebTokenProvider">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.NotificationHubs.TokenProvider CreateSimpleWebTokenProvider (string token, Microsoft.Azure.NotificationHubs.TokenScope tokenScope);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.NotificationHubs.TokenProvider CreateSimpleWebTokenProvider(string token, valuetype Microsoft.Azure.NotificationHubs.TokenScope tokenScope) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.NotificationHubs.TokenProvider.CreateSimpleWebTokenProvider(System.String,Microsoft.Azure.NotificationHubs.TokenScope)" />
      <MemberSignature Language="F#" Value="static member CreateSimpleWebTokenProvider : string * Microsoft.Azure.NotificationHubs.TokenScope -&gt; Microsoft.Azure.NotificationHubs.TokenProvider" Usage="Microsoft.Azure.NotificationHubs.TokenProvider.CreateSimpleWebTokenProvider (token, tokenScope)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.NotificationHubs.TokenProvider</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="token" Type="System.String" />
        <Parameter Name="tokenScope" Type="Microsoft.Azure.NotificationHubs.TokenScope" />
      </Parameters>
      <Docs>
        <param name="token">Die Zeichenfolge, die das simple webtoken darstellt.</param>
        <param name="tokenScope">Der token Bereich, der dem Anbieter zugeordnet ist.</param>
        <summary>Erstellt einen einfache Web-Tokenanbieter.</summary>
        <returns>Der erstellte einfache Web-Tokenanbieter.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateSimpleWebTokenProvider">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.NotificationHubs.TokenProvider CreateSimpleWebTokenProvider (string token, Uri stsUri);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.NotificationHubs.TokenProvider CreateSimpleWebTokenProvider(string token, class System.Uri stsUri) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.NotificationHubs.TokenProvider.CreateSimpleWebTokenProvider(System.String,System.Uri)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function CreateSimpleWebTokenProvider (token As String, stsUri As Uri) As TokenProvider" />
      <MemberSignature Language="F#" Value="static member CreateSimpleWebTokenProvider : string * Uri -&gt; Microsoft.Azure.NotificationHubs.TokenProvider" Usage="Microsoft.Azure.NotificationHubs.TokenProvider.CreateSimpleWebTokenProvider (token, stsUri)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.NotificationHubs.TokenProvider</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="token" Type="System.String" />
        <Parameter Name="stsUri" Type="System.Uri" />
      </Parameters>
      <Docs>
        <param name="token">Die Zeichenfolge, die das simple webtoken darstellt.</param>
        <param name="stsUri">Der URI der Sicherheitstokendienst (STS).</param>
        <summary>Erstellt einen einfache Web-Tokenanbieter.</summary>
        <returns>Die <see cref="T:Microsoft.Azure.NotificationHubs.TokenProvider" /> für die Rückgabe von einfachen webtoken.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateSimpleWebTokenProvider">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.NotificationHubs.TokenProvider CreateSimpleWebTokenProvider (string token, Uri stsUri, Microsoft.Azure.NotificationHubs.TokenScope tokenScope);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.NotificationHubs.TokenProvider CreateSimpleWebTokenProvider(string token, class System.Uri stsUri, valuetype Microsoft.Azure.NotificationHubs.TokenScope tokenScope) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.NotificationHubs.TokenProvider.CreateSimpleWebTokenProvider(System.String,System.Uri,Microsoft.Azure.NotificationHubs.TokenScope)" />
      <MemberSignature Language="F#" Value="static member CreateSimpleWebTokenProvider : string * Uri * Microsoft.Azure.NotificationHubs.TokenScope -&gt; Microsoft.Azure.NotificationHubs.TokenProvider" Usage="Microsoft.Azure.NotificationHubs.TokenProvider.CreateSimpleWebTokenProvider (token, stsUri, tokenScope)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.NotificationHubs.TokenProvider</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="token" Type="System.String" />
        <Parameter Name="stsUri" Type="System.Uri" />
        <Parameter Name="tokenScope" Type="Microsoft.Azure.NotificationHubs.TokenScope" />
      </Parameters>
      <Docs>
        <param name="token">Die Zeichenfolge, die das simple webtoken darstellt.</param>
        <param name="stsUri">Der URI der Sicherheitstokendienst (STS).</param>
        <param name="tokenScope">Der token Bereich, der dem Anbieter zugeordnet ist.</param>
        <summary>Erstellt einen einfache Web-Tokenanbieter.</summary>
        <returns>Der erstellte einfache Web-Tokenanbieter.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateWindowsTokenProvider">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.NotificationHubs.TokenProvider CreateWindowsTokenProvider (System.Collections.Generic.IEnumerable&lt;Uri&gt; stsUris);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.NotificationHubs.TokenProvider CreateWindowsTokenProvider(class System.Collections.Generic.IEnumerable`1&lt;class System.Uri&gt; stsUris) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.NotificationHubs.TokenProvider.CreateWindowsTokenProvider(System.Collections.Generic.IEnumerable{System.Uri})" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function CreateWindowsTokenProvider (stsUris As IEnumerable(Of Uri)) As TokenProvider" />
      <MemberSignature Language="F#" Value="static member CreateWindowsTokenProvider : seq&lt;Uri&gt; -&gt; Microsoft.Azure.NotificationHubs.TokenProvider" Usage="Microsoft.Azure.NotificationHubs.TokenProvider.CreateWindowsTokenProvider stsUris" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.NotificationHubs.TokenProvider</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="stsUris" Type="System.Collections.Generic.IEnumerable&lt;System.Uri&gt;" />
      </Parameters>
      <Docs>
        <param name="stsUris">Die URIs der Sicherheitstokendienst (STS).</param>
        <summary>Erstellt einen Windows-Tokenanbieter.</summary>
        <returns>Die <see cref="T:Microsoft.Azure.NotificationHubs.TokenProvider" /> für das Windows-Token zurückgeben.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateWindowsTokenProvider">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.NotificationHubs.TokenProvider CreateWindowsTokenProvider (System.Collections.Generic.IEnumerable&lt;Uri&gt; stsUris, System.Net.NetworkCredential credential);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.NotificationHubs.TokenProvider CreateWindowsTokenProvider(class System.Collections.Generic.IEnumerable`1&lt;class System.Uri&gt; stsUris, class System.Net.NetworkCredential credential) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.NotificationHubs.TokenProvider.CreateWindowsTokenProvider(System.Collections.Generic.IEnumerable{System.Uri},System.Net.NetworkCredential)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function CreateWindowsTokenProvider (stsUris As IEnumerable(Of Uri), credential As NetworkCredential) As TokenProvider" />
      <MemberSignature Language="F#" Value="static member CreateWindowsTokenProvider : seq&lt;Uri&gt; * System.Net.NetworkCredential -&gt; Microsoft.Azure.NotificationHubs.TokenProvider" Usage="Microsoft.Azure.NotificationHubs.TokenProvider.CreateWindowsTokenProvider (stsUris, credential)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.NotificationHubs.TokenProvider</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="stsUris" Type="System.Collections.Generic.IEnumerable&lt;System.Uri&gt;" />
        <Parameter Name="credential" Type="System.Net.NetworkCredential" />
      </Parameters>
      <Docs>
        <param name="stsUris">Die URIs der Sicherheitstokendienst (STS).</param>
        <param name="credential">Die Anmeldeinformationen des Benutzers.</param>
        <summary>Erstellt einen Windows-Tokenanbieter.</summary>
        <returns>Die <see cref="T:Microsoft.Azure.NotificationHubs.TokenProvider" /> für das Windows-Token zurückgeben.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="EndGetToken">
      <MemberSignature Language="C#" Value="public System.IdentityModel.Tokens.SecurityToken EndGetToken (IAsyncResult result);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.IdentityModel.Tokens.SecurityToken EndGetToken(class System.IAsyncResult result) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.NotificationHubs.TokenProvider.EndGetToken(System.IAsyncResult)" />
      <MemberSignature Language="VB.NET" Value="Public Function EndGetToken (result As IAsyncResult) As SecurityToken" />
      <MemberSignature Language="F#" Value="member this.EndGetToken : IAsyncResult -&gt; System.IdentityModel.Tokens.SecurityToken" Usage="tokenProvider.EndGetToken result" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.IdentityModel.Tokens.SecurityToken</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="result" Type="System.IAsyncResult" />
      </Parameters>
      <Docs>
        <param name="result">Ein <see cref="T:System.IAsyncResult" /> Objekt, das den asynchronen Vorgang zum Abrufen eines Tokens verweist.</param>
        <summary>Schließt einen asynchronen Vorgang ab, um ein Sicherheitstoken abzurufen.</summary>
        <returns>Das <see cref="T:System.IdentityModel.Tokens.SecurityToken" />-Objekt.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="EndGetWebToken">
      <MemberSignature Language="C#" Value="public string EndGetWebToken (IAsyncResult result);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance string EndGetWebToken(class System.IAsyncResult result) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.NotificationHubs.TokenProvider.EndGetWebToken(System.IAsyncResult)" />
      <MemberSignature Language="VB.NET" Value="Public Function EndGetWebToken (result As IAsyncResult) As String" />
      <MemberSignature Language="F#" Value="member this.EndGetWebToken : IAsyncResult -&gt; string" Usage="tokenProvider.EndGetWebToken result" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="result" Type="System.IAsyncResult" />
      </Parameters>
      <Docs>
        <param name="result">Ein <see cref="T:System.IAsyncResult" /> Objekt, das den asynchronen Vorgang zum Abrufen einer webtoken verweist.</param>
        <summary>Schließt einen asynchronen Vorgang zum Abrufen einer webtoken.</summary>
        <returns>Die <see cref="T:System.String" /> , die das webtoken darstellt.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetTokenAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.IdentityModel.Tokens.SecurityToken&gt; GetTokenAsync (string appliesTo, string action, bool bypassCache, TimeSpan timeout);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.IdentityModel.Tokens.SecurityToken&gt; GetTokenAsync(string appliesTo, string action, bool bypassCache, valuetype System.TimeSpan timeout) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.NotificationHubs.TokenProvider.GetTokenAsync(System.String,System.String,System.Boolean,System.TimeSpan)" />
      <MemberSignature Language="VB.NET" Value="Public Function GetTokenAsync (appliesTo As String, action As String, bypassCache As Boolean, timeout As TimeSpan) As Task(Of SecurityToken)" />
      <MemberSignature Language="F#" Value="member this.GetTokenAsync : string * string * bool * TimeSpan -&gt; System.Threading.Tasks.Task&lt;System.IdentityModel.Tokens.SecurityToken&gt;" Usage="tokenProvider.GetTokenAsync (appliesTo, action, bypassCache, timeout)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.IdentityModel.Tokens.SecurityToken&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="appliesTo" Type="System.String" />
        <Parameter Name="action" Type="System.String" />
        <Parameter Name="bypassCache" Type="System.Boolean" />
        <Parameter Name="timeout" Type="System.TimeSpan" />
      </Parameters>
      <Docs>
        <param name="appliesTo">Der URI, der das Zugriffstoken gilt.</param>
        <param name="action">Die anforderungsaktion.</param>
        <param name="bypassCache">"true", um vorhandene Tokeninformationen im Cache zu ignorieren; "false", der token Informationen im Cache zu verwenden.</param>
        <param name="timeout">Die Zeitspanne, die den Timeoutwert für die Nachricht gibt an, die Ruft das Sicherheitstoken ab.</param>
        <summary>Asynchron Ruft das Token für den Anbieter ab.</summary>
        <returns>Das Ergebnis des asynchronen Vorgangs.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetWebTokenAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;string&gt; GetWebTokenAsync (string appliesTo, string action, bool bypassCache, TimeSpan timeout);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;string&gt; GetWebTokenAsync(string appliesTo, string action, bool bypassCache, valuetype System.TimeSpan timeout) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.NotificationHubs.TokenProvider.GetWebTokenAsync(System.String,System.String,System.Boolean,System.TimeSpan)" />
      <MemberSignature Language="VB.NET" Value="Public Function GetWebTokenAsync (appliesTo As String, action As String, bypassCache As Boolean, timeout As TimeSpan) As Task(Of String)" />
      <MemberSignature Language="F#" Value="member this.GetWebTokenAsync : string * string * bool * TimeSpan -&gt; System.Threading.Tasks.Task&lt;string&gt;" Usage="tokenProvider.GetWebTokenAsync (appliesTo, action, bypassCache, timeout)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.String&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="appliesTo" Type="System.String" />
        <Parameter Name="action" Type="System.String" />
        <Parameter Name="bypassCache" Type="System.Boolean" />
        <Parameter Name="timeout" Type="System.TimeSpan" />
      </Parameters>
      <Docs>
        <param name="appliesTo">Der URI, der das Zugriffstoken gilt.</param>
        <param name="action">Die anforderungsaktion.</param>
        <param name="bypassCache">"true", um vorhandene Tokeninformationen im Cache zu ignorieren; "false", der token Informationen im Cache zu verwenden.</param>
        <param name="timeout">Die Zeitspanne, die den Timeoutwert für die Nachricht gibt an, die Ruft das Sicherheitstoken ab.</param>
        <summary>Ruft Sie die webtoken für den Anbieter asynchron ab.</summary>
        <returns>Das Ergebnis des asynchronen Vorgangs.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="IsWebTokenSupported">
      <MemberSignature Language="C#" Value="public bool IsWebTokenSupported { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance bool IsWebTokenSupported" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.NotificationHubs.TokenProvider.IsWebTokenSupported" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property IsWebTokenSupported As Boolean" />
      <MemberSignature Language="F#" Value="member this.IsWebTokenSupported : bool" Usage="Microsoft.Azure.NotificationHubs.TokenProvider.IsWebTokenSupported" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>Ruft ab oder legt einen Wert, der angibt, ob webtoken von diesem Anbieter unterstützt wird.</summary>
        <value>"true", wenn webtoken von diesem Anbieter unterstützt wird; andernfalls "false".</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="NormalizeAppliesTo">
      <MemberSignature Language="C#" Value="protected virtual string NormalizeAppliesTo (string appliesTo);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig newslot virtual instance string NormalizeAppliesTo(string appliesTo) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.NotificationHubs.TokenProvider.NormalizeAppliesTo(System.String)" />
      <MemberSignature Language="VB.NET" Value="Protected Overridable Function NormalizeAppliesTo (appliesTo As String) As String" />
      <MemberSignature Language="F#" Value="abstract member NormalizeAppliesTo : string -&gt; string&#xA;override this.NormalizeAppliesTo : string -&gt; string" Usage="tokenProvider.NormalizeAppliesTo appliesTo" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="appliesTo" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="appliesTo">Der URI, der das Zugriffstoken gilt.</param>
        <summary>Gibt ein Objekt, dessen Wert der Tokenanbieter identisch ist.</summary>
        <returns>Das zurückgegebene Objekt.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OnBeginGetToken">
      <MemberSignature Language="C#" Value="protected abstract IAsyncResult OnBeginGetToken (string appliesTo, string action, TimeSpan timeout, AsyncCallback callback, object state);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig newslot virtual instance class System.IAsyncResult OnBeginGetToken(string appliesTo, string action, valuetype System.TimeSpan timeout, class System.AsyncCallback callback, object state) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.NotificationHubs.TokenProvider.OnBeginGetToken(System.String,System.String,System.TimeSpan,System.AsyncCallback,System.Object)" />
      <MemberSignature Language="VB.NET" Value="Protected MustOverride Function OnBeginGetToken (appliesTo As String, action As String, timeout As TimeSpan, callback As AsyncCallback, state As Object) As IAsyncResult" />
      <MemberSignature Language="F#" Value="abstract member OnBeginGetToken : string * string * TimeSpan * AsyncCallback * obj -&gt; IAsyncResult" Usage="tokenProvider.OnBeginGetToken (appliesTo, action, timeout, callback, state)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.IAsyncResult</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="appliesTo" Type="System.String" />
        <Parameter Name="action" Type="System.String" />
        <Parameter Name="timeout" Type="System.TimeSpan" />
        <Parameter Name="callback" Type="System.AsyncCallback" />
        <Parameter Name="state" Type="System.Object" />
      </Parameters>
      <Docs>
        <param name="appliesTo">Der URI, der das Zugriffstoken gilt.</param>
        <param name="action">Die anforderungsaktion.</param>
        <param name="timeout">Die Zeitspanne, die den Timeoutwert für die Nachricht gibt an, die Ruft das Sicherheitstoken ab.</param>
        <param name="callback">Ein <see cref="T:System.AsyncCallback" />-Delegat, der auf die Methode verweist, die bei Abschluss des Vorgangs aufgerufen werden soll.</param>
        <param name="state">Ein benutzerdefiniertes Objekt, das Statusinformationen über den asynchronen Vorgang enthält. </param>
        <summary>Führt beim Aufrufen der BeginGetToken-Methode.</summary>
        <returns>Ein <see cref="T:System.IAsyncResult" /> Objekt, das den asynchronen Vorgang zum Abrufen eines Tokens verweist.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OnBeginGetWebToken">
      <MemberSignature Language="C#" Value="protected abstract IAsyncResult OnBeginGetWebToken (string appliesTo, string action, TimeSpan timeout, AsyncCallback callback, object state);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig newslot virtual instance class System.IAsyncResult OnBeginGetWebToken(string appliesTo, string action, valuetype System.TimeSpan timeout, class System.AsyncCallback callback, object state) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.NotificationHubs.TokenProvider.OnBeginGetWebToken(System.String,System.String,System.TimeSpan,System.AsyncCallback,System.Object)" />
      <MemberSignature Language="VB.NET" Value="Protected MustOverride Function OnBeginGetWebToken (appliesTo As String, action As String, timeout As TimeSpan, callback As AsyncCallback, state As Object) As IAsyncResult" />
      <MemberSignature Language="F#" Value="abstract member OnBeginGetWebToken : string * string * TimeSpan * AsyncCallback * obj -&gt; IAsyncResult" Usage="tokenProvider.OnBeginGetWebToken (appliesTo, action, timeout, callback, state)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.IAsyncResult</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="appliesTo" Type="System.String" />
        <Parameter Name="action" Type="System.String" />
        <Parameter Name="timeout" Type="System.TimeSpan" />
        <Parameter Name="callback" Type="System.AsyncCallback" />
        <Parameter Name="state" Type="System.Object" />
      </Parameters>
      <Docs>
        <param name="appliesTo">Der URI, der das Zugriffstoken gilt.</param>
        <param name="action">Die anforderungsaktion.</param>
        <param name="timeout">Die Zeitspanne, die den Timeoutwert für die Nachricht gibt an, die Ruft das Sicherheitstoken ab.</param>
        <param name="callback">Ein <see cref="T:System.AsyncCallback" />-Delegat, der auf die Methode verweist, die bei Abschluss des Vorgangs aufgerufen werden soll.</param>
        <param name="state">Ein benutzerdefiniertes Objekt, das Statusinformationen über den asynchronen Vorgang enthält. </param>
        <summary>Führt beim Aufrufen der BeginGetWebToken-Methode.</summary>
        <returns>Ein <see cref="T:System.IAsyncResult" /> Objekt, das den asynchronen Vorgang zum Abrufen einer webtoken verweist.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OnEndGetToken">
      <MemberSignature Language="C#" Value="protected abstract System.IdentityModel.Tokens.SecurityToken OnEndGetToken (IAsyncResult result, out DateTime cacheUntil);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig newslot virtual instance class System.IdentityModel.Tokens.SecurityToken OnEndGetToken(class System.IAsyncResult result, [out] valuetype System.DateTime&amp; cacheUntil) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.NotificationHubs.TokenProvider.OnEndGetToken(System.IAsyncResult,System.DateTime@)" />
      <MemberSignature Language="VB.NET" Value="Protected MustOverride Function OnEndGetToken (result As IAsyncResult, ByRef cacheUntil As DateTime) As SecurityToken" />
      <MemberSignature Language="F#" Value="abstract member OnEndGetToken : IAsyncResult *  -&gt; System.IdentityModel.Tokens.SecurityToken" Usage="tokenProvider.OnEndGetToken (result, cacheUntil)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.IdentityModel.Tokens.SecurityToken</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="result" Type="System.IAsyncResult" />
        <Parameter Name="cacheUntil" Type="System.DateTime&amp;" RefType="out" />
      </Parameters>
      <Docs>
        <param name="result">Ein <see cref="T:System.IAsyncResult" /> Objekt, das den asynchronen Vorgang zum Abrufen eines Tokens verweist.</param>
        <param name="cacheUntil">Wenn diese Methode zurückgibt, enthält das Ablaufdatum und die Uhrzeit der token Informationen im Cache.</param>
        <summary>Führt beim Aufrufen der EndGetToken-Methode.</summary>
        <returns>Das <see cref="T:System.IdentityModel.Tokens.SecurityToken" />-Objekt.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OnEndGetWebToken">
      <MemberSignature Language="C#" Value="protected abstract string OnEndGetWebToken (IAsyncResult result, out DateTime cacheUntil);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig newslot virtual instance string OnEndGetWebToken(class System.IAsyncResult result, [out] valuetype System.DateTime&amp; cacheUntil) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.NotificationHubs.TokenProvider.OnEndGetWebToken(System.IAsyncResult,System.DateTime@)" />
      <MemberSignature Language="VB.NET" Value="Protected MustOverride Function OnEndGetWebToken (result As IAsyncResult, ByRef cacheUntil As DateTime) As String" />
      <MemberSignature Language="F#" Value="abstract member OnEndGetWebToken : IAsyncResult *  -&gt; string" Usage="tokenProvider.OnEndGetWebToken (result, cacheUntil)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="result" Type="System.IAsyncResult" />
        <Parameter Name="cacheUntil" Type="System.DateTime&amp;" RefType="out" />
      </Parameters>
      <Docs>
        <param name="result">Ein <see cref="T:System.IAsyncResult" /> Objekt, das den asynchronen Vorgang zum Abrufen einer webtoken verweist.</param>
        <param name="cacheUntil">Wenn diese Methode zurückgibt, enthält das Ablaufdatum und die Uhrzeit der token Informationen im Cache.</param>
        <summary>Führt beim Aufrufen der EndGetWebToken-Methode.</summary>
        <returns>Die <see cref="T:System.String" /> , die das webtoken darstellt.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="StripQueryParameters">
      <MemberSignature Language="C#" Value="protected virtual bool StripQueryParameters { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance bool StripQueryParameters" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.NotificationHubs.TokenProvider.StripQueryParameters" />
      <MemberSignature Language="VB.NET" Value="Protected Overridable ReadOnly Property StripQueryParameters As Boolean" />
      <MemberSignature Language="F#" Value="member this.StripQueryParameters : bool" Usage="Microsoft.Azure.NotificationHubs.TokenProvider.StripQueryParameters" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>Ruft ab, ob der Tokenanbieter Abfrageparameter entfernt.</summary>
        <value>"true", wenn der Tokenanbieter Abfrageparameter entfernt; andernfalls "false".</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="TokenScope">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.NotificationHubs.TokenScope TokenScope { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype Microsoft.Azure.NotificationHubs.TokenScope TokenScope" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.NotificationHubs.TokenProvider.TokenScope" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property TokenScope As TokenScope" />
      <MemberSignature Language="F#" Value="member this.TokenScope : Microsoft.Azure.NotificationHubs.TokenScope" Usage="Microsoft.Azure.NotificationHubs.TokenProvider.TokenScope" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.NotificationHubs.TokenScope</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>Ermittelt oder definiert das token Bereich, der dem Anbieter zugeordnet.</summary>
        <value>Der token Bereich, der dem Anbieter zugeordnet ist.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>