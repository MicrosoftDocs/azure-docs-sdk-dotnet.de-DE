<Type Name="IMobileServiceTable" FullName="Microsoft.WindowsAzure.MobileServices.IMobileServiceTable">
  <TypeSignature Language="C#" Value="public interface IMobileServiceTable" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IMobileServiceTable" />
  <TypeSignature Language="DocId" Value="T:Microsoft.WindowsAzure.MobileServices.IMobileServiceTable" />
  <TypeSignature Language="VB.NET" Value="Public Interface IMobileServiceTable" />
  <TypeSignature Language="F#" Value="type IMobileServiceTable = interface" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Mobile.Client</AssemblyName>
    <AssemblyVersion>4.0.0.0</AssemblyVersion>
    <AssemblyVersion>4.0.2.0</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces />
  <Docs>
    <summary>
            Stellt Vorgänge für eine Tabelle für Microsoft Azure Mobile Service bereit.
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="DeleteAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Newtonsoft.Json.Linq.JToken&gt; DeleteAsync (Newtonsoft.Json.Linq.JObject instance);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Newtonsoft.Json.Linq.JToken&gt; DeleteAsync(class Newtonsoft.Json.Linq.JObject instance) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.MobileServices.IMobileServiceTable.DeleteAsync(Newtonsoft.Json.Linq.JObject)" />
      <MemberSignature Language="VB.NET" Value="Public Function DeleteAsync (instance As JObject) As Task(Of JToken)" />
      <MemberSignature Language="F#" Value="abstract member DeleteAsync : Newtonsoft.Json.Linq.JObject -&gt; System.Threading.Tasks.Task&lt;Newtonsoft.Json.Linq.JToken&gt;" Usage="iMobileServiceTable.DeleteAsync instance" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Mobile.Client</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.2.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Newtonsoft.Json.Linq.JToken&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="instance" Type="Newtonsoft.Json.Linq.JObject" />
      </Parameters>
      <Docs>
        <param name="instance">
            Die Instanz, aus der Tabelle löschen.
            </param>
        <summary>
            Löscht eine <paramref name="instance" /> aus der Tabelle.
            </summary>
        <returns>
            Eine Aufgabe, die abgeschlossen wird, wenn der Löschvorgang abgeschlossen ist.
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeleteAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Newtonsoft.Json.Linq.JToken&gt; DeleteAsync (Newtonsoft.Json.Linq.JObject instance, System.Collections.Generic.IDictionary&lt;string,string&gt; parameters);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Newtonsoft.Json.Linq.JToken&gt; DeleteAsync(class Newtonsoft.Json.Linq.JObject instance, class System.Collections.Generic.IDictionary`2&lt;string, string&gt; parameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.MobileServices.IMobileServiceTable.DeleteAsync(Newtonsoft.Json.Linq.JObject,System.Collections.Generic.IDictionary{System.String,System.String})" />
      <MemberSignature Language="VB.NET" Value="Public Function DeleteAsync (instance As JObject, parameters As IDictionary(Of String, String)) As Task(Of JToken)" />
      <MemberSignature Language="F#" Value="abstract member DeleteAsync : Newtonsoft.Json.Linq.JObject * System.Collections.Generic.IDictionary&lt;string, string&gt; -&gt; System.Threading.Tasks.Task&lt;Newtonsoft.Json.Linq.JToken&gt;" Usage="iMobileServiceTable.DeleteAsync (instance, parameters)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Mobile.Client</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.2.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Newtonsoft.Json.Linq.JToken&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="instance" Type="Newtonsoft.Json.Linq.JObject" />
        <Parameter Name="parameters" Type="System.Collections.Generic.IDictionary&lt;System.String,System.String&gt;" />
      </Parameters>
      <Docs>
        <param name="instance">
            Die Instanz, aus der Tabelle löschen.
            </param>
        <param name="parameters">
            Ein Wörterbuch mit benutzerdefinierten Parametern und Werten, die im Anforderungs-URI-Abfragezeichenfolge enthalten.
            </param>
        <summary>
            Löscht eine <paramref name="instance" /> aus der Tabelle.
            </summary>
        <returns>
            Eine Aufgabe, die abgeschlossen wird, wenn der Löschvorgang abgeschlossen ist.
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="InsertAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Newtonsoft.Json.Linq.JToken&gt; InsertAsync (Newtonsoft.Json.Linq.JObject instance);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Newtonsoft.Json.Linq.JToken&gt; InsertAsync(class Newtonsoft.Json.Linq.JObject instance) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.MobileServices.IMobileServiceTable.InsertAsync(Newtonsoft.Json.Linq.JObject)" />
      <MemberSignature Language="VB.NET" Value="Public Function InsertAsync (instance As JObject) As Task(Of JToken)" />
      <MemberSignature Language="F#" Value="abstract member InsertAsync : Newtonsoft.Json.Linq.JObject -&gt; System.Threading.Tasks.Task&lt;Newtonsoft.Json.Linq.JToken&gt;" Usage="iMobileServiceTable.InsertAsync instance" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Mobile.Client</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.2.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Newtonsoft.Json.Linq.JToken&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="instance" Type="Newtonsoft.Json.Linq.JObject" />
      </Parameters>
      <Docs>
        <param name="instance">
            Die Instanz, in die Tabelle einzufügen.
            </param>
        <summary>
            Fügt eine <paramref name="instance" /> in die Tabelle.
            </summary>
        <returns>
            Eine Aufgabe, die abgeschlossen wird, wenn der Einfügevorgang abgeschlossen ist.
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="InsertAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Newtonsoft.Json.Linq.JToken&gt; InsertAsync (Newtonsoft.Json.Linq.JObject instance, System.Collections.Generic.IDictionary&lt;string,string&gt; parameters);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Newtonsoft.Json.Linq.JToken&gt; InsertAsync(class Newtonsoft.Json.Linq.JObject instance, class System.Collections.Generic.IDictionary`2&lt;string, string&gt; parameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.MobileServices.IMobileServiceTable.InsertAsync(Newtonsoft.Json.Linq.JObject,System.Collections.Generic.IDictionary{System.String,System.String})" />
      <MemberSignature Language="VB.NET" Value="Public Function InsertAsync (instance As JObject, parameters As IDictionary(Of String, String)) As Task(Of JToken)" />
      <MemberSignature Language="F#" Value="abstract member InsertAsync : Newtonsoft.Json.Linq.JObject * System.Collections.Generic.IDictionary&lt;string, string&gt; -&gt; System.Threading.Tasks.Task&lt;Newtonsoft.Json.Linq.JToken&gt;" Usage="iMobileServiceTable.InsertAsync (instance, parameters)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Mobile.Client</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.2.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Newtonsoft.Json.Linq.JToken&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="instance" Type="Newtonsoft.Json.Linq.JObject" />
        <Parameter Name="parameters" Type="System.Collections.Generic.IDictionary&lt;System.String,System.String&gt;" />
      </Parameters>
      <Docs>
        <param name="instance">
            Die Instanz, in die Tabelle einzufügen.
            </param>
        <param name="parameters">
            Ein Wörterbuch mit benutzerdefinierten Parametern und Werten, die im Anforderungs-URI-Abfragezeichenfolge enthalten.
            </param>
        <summary>
            Fügt eine <paramref name="instance" /> in die Tabelle.
            </summary>
        <returns>
            Eine Aufgabe, die abgeschlossen wird, wenn der Einfügevorgang abgeschlossen ist.
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="LookupAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Newtonsoft.Json.Linq.JToken&gt; LookupAsync (object id);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Newtonsoft.Json.Linq.JToken&gt; LookupAsync(object id) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.MobileServices.IMobileServiceTable.LookupAsync(System.Object)" />
      <MemberSignature Language="VB.NET" Value="Public Function LookupAsync (id As Object) As Task(Of JToken)" />
      <MemberSignature Language="F#" Value="abstract member LookupAsync : obj -&gt; System.Threading.Tasks.Task&lt;Newtonsoft.Json.Linq.JToken&gt;" Usage="iMobileServiceTable.LookupAsync id" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Mobile.Client</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.2.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Newtonsoft.Json.Linq.JToken&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="id" Type="System.Object" />
      </Parameters>
      <Docs>
        <param name="id">
            Die Id des zu suchenden Instanz.
            </param>
        <summary>
            Führt eine Suche für eine Tabelle aus.
            </summary>
        <returns>
            Eine Aufgabe, die mit einem Ergebnis zurückgegeben wird, wenn die Suche abgeschlossen ist.
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="LookupAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Newtonsoft.Json.Linq.JToken&gt; LookupAsync (object id, System.Collections.Generic.IDictionary&lt;string,string&gt; parameters);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Newtonsoft.Json.Linq.JToken&gt; LookupAsync(object id, class System.Collections.Generic.IDictionary`2&lt;string, string&gt; parameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.MobileServices.IMobileServiceTable.LookupAsync(System.Object,System.Collections.Generic.IDictionary{System.String,System.String})" />
      <MemberSignature Language="VB.NET" Value="Public Function LookupAsync (id As Object, parameters As IDictionary(Of String, String)) As Task(Of JToken)" />
      <MemberSignature Language="F#" Value="abstract member LookupAsync : obj * System.Collections.Generic.IDictionary&lt;string, string&gt; -&gt; System.Threading.Tasks.Task&lt;Newtonsoft.Json.Linq.JToken&gt;" Usage="iMobileServiceTable.LookupAsync (id, parameters)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Mobile.Client</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.2.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Newtonsoft.Json.Linq.JToken&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="id" Type="System.Object" />
        <Parameter Name="parameters" Type="System.Collections.Generic.IDictionary&lt;System.String,System.String&gt;" />
      </Parameters>
      <Docs>
        <param name="id">
            Die Id des zu suchenden Instanz.
            </param>
        <param name="parameters">
            Ein Wörterbuch mit benutzerdefinierten Parametern und Werten, die im Anforderungs-URI-Abfragezeichenfolge enthalten.
            </param>
        <summary>
            Führt eine Suche für eine Tabelle aus.
            </summary>
        <returns>
            Eine Aufgabe, die mit einem Ergebnis zurückgegeben wird, wenn die Suche abgeschlossen ist.
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="MobileServiceClient">
      <MemberSignature Language="C#" Value="public Microsoft.WindowsAzure.MobileServices.MobileServiceClient MobileServiceClient { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.WindowsAzure.MobileServices.MobileServiceClient MobileServiceClient" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.MobileServices.IMobileServiceTable.MobileServiceClient" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property MobileServiceClient As MobileServiceClient" />
      <MemberSignature Language="F#" Value="member this.MobileServiceClient : Microsoft.WindowsAzure.MobileServices.MobileServiceClient" Usage="Microsoft.WindowsAzure.MobileServices.IMobileServiceTable.MobileServiceClient" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Mobile.Client</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.2.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.WindowsAzure.MobileServices.MobileServiceClient</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft einen Verweis auf die <see cref="P:Microsoft.WindowsAzure.MobileServices.IMobileServiceTable.MobileServiceClient" /> dieser Tabelle zugeordnet.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ReadAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Newtonsoft.Json.Linq.JToken&gt; ReadAsync (string query);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Newtonsoft.Json.Linq.JToken&gt; ReadAsync(string query) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.MobileServices.IMobileServiceTable.ReadAsync(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function ReadAsync (query As String) As Task(Of JToken)" />
      <MemberSignature Language="F#" Value="abstract member ReadAsync : string -&gt; System.Threading.Tasks.Task&lt;Newtonsoft.Json.Linq.JToken&gt;" Usage="iMobileServiceTable.ReadAsync query" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Mobile.Client</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.2.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Newtonsoft.Json.Linq.JToken&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="query" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="query">
            Eine auszuführende Abfrage.
            </param>
        <summary>
            Führt eine Abfrage für die Tabelle.
            </summary>
        <returns>
            Eine Aufgabe, die mit Ergebnissen zurückgegeben wird, wenn die Abfrage abgeschlossen ist.
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ReadAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Newtonsoft.Json.Linq.JToken&gt; ReadAsync (string query, System.Collections.Generic.IDictionary&lt;string,string&gt; parameters, bool wrapResult);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Newtonsoft.Json.Linq.JToken&gt; ReadAsync(string query, class System.Collections.Generic.IDictionary`2&lt;string, string&gt; parameters, bool wrapResult) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.MobileServices.IMobileServiceTable.ReadAsync(System.String,System.Collections.Generic.IDictionary{System.String,System.String},System.Boolean)" />
      <MemberSignature Language="VB.NET" Value="Public Function ReadAsync (query As String, parameters As IDictionary(Of String, String), wrapResult As Boolean) As Task(Of JToken)" />
      <MemberSignature Language="F#" Value="abstract member ReadAsync : string * System.Collections.Generic.IDictionary&lt;string, string&gt; * bool -&gt; System.Threading.Tasks.Task&lt;Newtonsoft.Json.Linq.JToken&gt;" Usage="iMobileServiceTable.ReadAsync (query, parameters, wrapResult)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Mobile.Client</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.2.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Newtonsoft.Json.Linq.JToken&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="query" Type="System.String" />
        <Parameter Name="parameters" Type="System.Collections.Generic.IDictionary&lt;System.String,System.String&gt;" />
        <Parameter Name="wrapResult" Type="System.Boolean" />
      </Parameters>
      <Docs>
        <param name="query">
            Eine auszuführende Abfrage.
            </param>
        <param name="parameters">
            Ein Wörterbuch mit benutzerdefinierten Parametern und Werten, die im Anforderungs-URI-Abfragezeichenfolge enthalten.
            </param>
        <param name="wrapResult">
            Gibt an, ob die Antwort als JObject zusätzliche Antwortdetails z. B. einschließlich Link Header formatiert werden soll
            </param>
        <summary>
            Führt eine Abfrage für die Tabelle.
            </summary>
        <returns>
            Eine Aufgabe, die mit Ergebnissen zurückgegeben wird, wenn die Abfrage abgeschlossen ist.
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="TableName">
      <MemberSignature Language="C#" Value="public string TableName { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string TableName" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.MobileServices.IMobileServiceTable.TableName" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property TableName As String" />
      <MemberSignature Language="F#" Value="member this.TableName : string" Usage="Microsoft.WindowsAzure.MobileServices.IMobileServiceTable.TableName" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Mobile.Client</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.2.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft den Namen der Tabelle ab.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UndeleteAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Newtonsoft.Json.Linq.JToken&gt; UndeleteAsync (Newtonsoft.Json.Linq.JObject instance);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Newtonsoft.Json.Linq.JToken&gt; UndeleteAsync(class Newtonsoft.Json.Linq.JObject instance) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.MobileServices.IMobileServiceTable.UndeleteAsync(Newtonsoft.Json.Linq.JObject)" />
      <MemberSignature Language="VB.NET" Value="Public Function UndeleteAsync (instance As JObject) As Task(Of JToken)" />
      <MemberSignature Language="F#" Value="abstract member UndeleteAsync : Newtonsoft.Json.Linq.JObject -&gt; System.Threading.Tasks.Task&lt;Newtonsoft.Json.Linq.JToken&gt;" Usage="iMobileServiceTable.UndeleteAsync instance" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Mobile.Client</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.2.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Newtonsoft.Json.Linq.JToken&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="instance" Type="Newtonsoft.Json.Linq.JObject" />
      </Parameters>
      <Docs>
        <param name="instance">Die Instanz, aus der Tabelle rückgängig machen.</param>
        <summary>
            Wiederherstellung von einer <paramref name="instance" /> aus der Tabelle. Dies erfordert die vorläufigen löschen Feature auf den mobilen Dienst aktiviert werden. Besuchen Sie <see href="http://go.microsoft.com/fwlink/?LinkId=507647">den Link</see> Details.
            </summary>
        <returns>Eine Aufgabe, die abgeschlossen wird, wenn die Wiederherstellung abgeschlossen ist.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UndeleteAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Newtonsoft.Json.Linq.JToken&gt; UndeleteAsync (Newtonsoft.Json.Linq.JObject instance, System.Collections.Generic.IDictionary&lt;string,string&gt; parameters);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Newtonsoft.Json.Linq.JToken&gt; UndeleteAsync(class Newtonsoft.Json.Linq.JObject instance, class System.Collections.Generic.IDictionary`2&lt;string, string&gt; parameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.MobileServices.IMobileServiceTable.UndeleteAsync(Newtonsoft.Json.Linq.JObject,System.Collections.Generic.IDictionary{System.String,System.String})" />
      <MemberSignature Language="VB.NET" Value="Public Function UndeleteAsync (instance As JObject, parameters As IDictionary(Of String, String)) As Task(Of JToken)" />
      <MemberSignature Language="F#" Value="abstract member UndeleteAsync : Newtonsoft.Json.Linq.JObject * System.Collections.Generic.IDictionary&lt;string, string&gt; -&gt; System.Threading.Tasks.Task&lt;Newtonsoft.Json.Linq.JToken&gt;" Usage="iMobileServiceTable.UndeleteAsync (instance, parameters)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Mobile.Client</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.2.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Newtonsoft.Json.Linq.JToken&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="instance" Type="Newtonsoft.Json.Linq.JObject" />
        <Parameter Name="parameters" Type="System.Collections.Generic.IDictionary&lt;System.String,System.String&gt;" />
      </Parameters>
      <Docs>
        <param name="instance">Die Instanz, aus der Tabelle rückgängig machen.</param>
        <param name="parameters">
            Ein Wörterbuch mit benutzerdefinierten Parametern und Werten, die im Anforderungs-URI-Abfragezeichenfolge enthalten.
            </param>
        <summary>
            Wiederherstellung von einer <paramref name="instance" /> aus der Tabelle. Dies erfordert die vorläufigen löschen Feature auf den mobilen Dienst aktiviert werden. Besuchen Sie <see href="http://go.microsoft.com/fwlink/?LinkId=507647">den Link</see> Details.
            </summary>
        <returns>Eine Aufgabe, die abgeschlossen wird, wenn die Wiederherstellung abgeschlossen ist.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UpdateAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Newtonsoft.Json.Linq.JToken&gt; UpdateAsync (Newtonsoft.Json.Linq.JObject instance);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Newtonsoft.Json.Linq.JToken&gt; UpdateAsync(class Newtonsoft.Json.Linq.JObject instance) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.MobileServices.IMobileServiceTable.UpdateAsync(Newtonsoft.Json.Linq.JObject)" />
      <MemberSignature Language="VB.NET" Value="Public Function UpdateAsync (instance As JObject) As Task(Of JToken)" />
      <MemberSignature Language="F#" Value="abstract member UpdateAsync : Newtonsoft.Json.Linq.JObject -&gt; System.Threading.Tasks.Task&lt;Newtonsoft.Json.Linq.JToken&gt;" Usage="iMobileServiceTable.UpdateAsync instance" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Mobile.Client</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.2.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Newtonsoft.Json.Linq.JToken&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="instance" Type="Newtonsoft.Json.Linq.JObject" />
      </Parameters>
      <Docs>
        <param name="instance">
            In der Tabelle zu aktualisierende Instanz.
            </param>
        <summary>
            Updates ein <paramref name="instance" /> in der Tabelle.
            </summary>
        <returns>
            Eine Aufgabe, die abgeschlossen wird, wenn der Aktualisierungsvorgang abgeschlossen ist.
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UpdateAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Newtonsoft.Json.Linq.JToken&gt; UpdateAsync (Newtonsoft.Json.Linq.JObject instance, System.Collections.Generic.IDictionary&lt;string,string&gt; parameters);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Newtonsoft.Json.Linq.JToken&gt; UpdateAsync(class Newtonsoft.Json.Linq.JObject instance, class System.Collections.Generic.IDictionary`2&lt;string, string&gt; parameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.MobileServices.IMobileServiceTable.UpdateAsync(Newtonsoft.Json.Linq.JObject,System.Collections.Generic.IDictionary{System.String,System.String})" />
      <MemberSignature Language="VB.NET" Value="Public Function UpdateAsync (instance As JObject, parameters As IDictionary(Of String, String)) As Task(Of JToken)" />
      <MemberSignature Language="F#" Value="abstract member UpdateAsync : Newtonsoft.Json.Linq.JObject * System.Collections.Generic.IDictionary&lt;string, string&gt; -&gt; System.Threading.Tasks.Task&lt;Newtonsoft.Json.Linq.JToken&gt;" Usage="iMobileServiceTable.UpdateAsync (instance, parameters)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Mobile.Client</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.2.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Newtonsoft.Json.Linq.JToken&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="instance" Type="Newtonsoft.Json.Linq.JObject" />
        <Parameter Name="parameters" Type="System.Collections.Generic.IDictionary&lt;System.String,System.String&gt;" />
      </Parameters>
      <Docs>
        <param name="instance">
            In der Tabelle zu aktualisierende Instanz.
            </param>
        <param name="parameters">
            Ein Wörterbuch mit benutzerdefinierten Parametern und Werten, die im Anforderungs-URI-Abfragezeichenfolge enthalten.
            </param>
        <summary>
            Updates ein <paramref name="instance" /> in der Tabelle.
            </summary>
        <returns>
            Eine Aufgabe, die abgeschlossen wird, wenn der Aktualisierungsvorgang abgeschlossen ist.
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>