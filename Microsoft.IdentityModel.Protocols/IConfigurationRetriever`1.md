<Type Name="IConfigurationRetriever&lt;T&gt;" FullName="Microsoft.IdentityModel.Protocols.IConfigurationRetriever&lt;T&gt;">
  <TypeSignature Language="C#" Value="public interface IConfigurationRetriever&lt;T&gt;" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IConfigurationRetriever`1&lt;T&gt;" />
  <TypeSignature Language="DocId" Value="T:Microsoft.IdentityModel.Protocols.IConfigurationRetriever`1" />
  <TypeSignature Language="VB.NET" Value="Public Interface IConfigurationRetriever(Of T)" />
  <TypeSignature Language="F#" Value="type IConfigurationRetriever&lt;'T&gt; = interface" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.IdentityModel.Protocols</AssemblyName>
    <AssemblyVersion>2.1.3.0</AssemblyVersion>
    <AssemblyVersion>5.2.0.0</AssemblyVersion>
  </AssemblyInfo>
  <TypeParameters>
    <TypeParameter Name="T" />
  </TypeParameters>
  <Interfaces />
  <Docs>
    <typeparam name="T">Der Typ der Konfigurationsmetadaten.</typeparam>
    <summary>
            Schnittstelle, die Methoden zum Abrufen von Konfiguration definiert.
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="GetConfigurationAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;T&gt; GetConfigurationAsync (string address, Microsoft.IdentityModel.Protocols.IDocumentRetriever retriever, System.Threading.CancellationToken cancel);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;!T&gt; GetConfigurationAsync(string address, class Microsoft.IdentityModel.Protocols.IDocumentRetriever retriever, valuetype System.Threading.CancellationToken cancel) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.IdentityModel.Protocols.IConfigurationRetriever`1.GetConfigurationAsync(System.String,Microsoft.IdentityModel.Protocols.IDocumentRetriever,System.Threading.CancellationToken)" />
      <MemberSignature Language="VB.NET" Value="Public Function GetConfigurationAsync (address As String, retriever As IDocumentRetriever, cancel As CancellationToken) As Task(Of T)" />
      <MemberSignature Language="F#" Value="abstract member GetConfigurationAsync : string * Microsoft.IdentityModel.Protocols.IDocumentRetriever * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;'T&gt;" Usage="iConfigurationRetriever.GetConfigurationAsync (address, retriever, cancel)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.IdentityModel.Protocols</AssemblyName>
        <AssemblyVersion>2.1.3.0</AssemblyVersion>
        <AssemblyVersion>5.2.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;T&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="address" Type="System.String" />
        <Parameter Name="retriever" Type="Microsoft.IdentityModel.Protocols.IDocumentRetriever" />
        <Parameter Name="cancel" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="address">Die Adresse des Discovery-Dokuments.</param>
        <param name="retriever">Die <see cref="T:Microsoft.IdentityModel.Protocols.IDocumentRetriever" /> zu verwenden, um den Discoverydokument zu lesen.</param>
        <param name="cancel">Ein Abbruchtoken, das von anderen Objekten oder Threads verwendet werden kann, um Nachricht vom Abbruch zu empfangen. <see cref="T:System.Threading.CancellationToken" />(Fixierte Verbindung) festgelegt ist(Fixierte Verbindung) festgelegt ist.</param>
        <summary>
            Ruft eine ausgefüllte Konfiguration erhält eine Adresse und ein <see cref="T:Microsoft.IdentityModel.Protocols.IDocumentRetriever" />.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>