<Type Name="MobileServiceTableExtensions" FullName="Microsoft.WindowsAzure.MobileServices.MobileServiceTableExtensions">
  <TypeSignature Language="C#" Value="public static class MobileServiceTableExtensions" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract sealed beforefieldinit MobileServiceTableExtensions extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.WindowsAzure.MobileServices.MobileServiceTableExtensions" />
  <TypeSignature Language="VB.NET" Value="Public Module MobileServiceTableExtensions" />
  <TypeSignature Language="F#" Value="type MobileServiceTableExtensions = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Mobile.Client</AssemblyName>
    <AssemblyVersion>4.0.0.0</AssemblyVersion>
    <AssemblyVersion>4.0.2.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            Enthält Erweiterungsmethoden [c#]<see cref="T:Microsoft.WindowsAzure.MobileServices.IMobileServiceTable" /></summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="ReadAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Newtonsoft.Json.Linq.JToken&gt; ReadAsync (this Microsoft.WindowsAzure.MobileServices.IMobileServiceTable table, string query, System.Collections.Generic.IDictionary&lt;string,string&gt; parameters);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Newtonsoft.Json.Linq.JToken&gt; ReadAsync(class Microsoft.WindowsAzure.MobileServices.IMobileServiceTable table, string query, class System.Collections.Generic.IDictionary`2&lt;string, string&gt; parameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.MobileServices.MobileServiceTableExtensions.ReadAsync(Microsoft.WindowsAzure.MobileServices.IMobileServiceTable,System.String,System.Collections.Generic.IDictionary{System.String,System.String})" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ReadAsync (table As IMobileServiceTable, query As String, parameters As IDictionary(Of String, String)) As Task(Of JToken)" />
      <MemberSignature Language="F#" Value="static member ReadAsync : Microsoft.WindowsAzure.MobileServices.IMobileServiceTable * string * System.Collections.Generic.IDictionary&lt;string, string&gt; -&gt; System.Threading.Tasks.Task&lt;Newtonsoft.Json.Linq.JToken&gt;" Usage="Microsoft.WindowsAzure.MobileServices.MobileServiceTableExtensions.ReadAsync (table, query, parameters)" />
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
        <Parameter Name="table" Type="Microsoft.WindowsAzure.MobileServices.IMobileServiceTable" RefType="this" />
        <Parameter Name="query" Type="System.String" />
        <Parameter Name="parameters" Type="System.Collections.Generic.IDictionary&lt;System.String,System.String&gt;" />
      </Parameters>
      <Docs>
        <param name="table">
            Die Instanz der Tabelle, aus dem gelesen werden soll.
            </param>
        <param name="query">
            Eine auszuführende Abfrage.
            </param>
        <param name="parameters">
            Ein Wörterbuch mit benutzerdefinierten Parametern und Werten, die im Anforderungs-URI-Abfragezeichenfolge enthalten.
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
  </Members>
</Type>