<Type Name="IConfigurationManager&lt;T&gt;" FullName="Microsoft.IdentityModel.Protocols.IConfigurationManager&lt;T&gt;">
  <TypeSignature Language="C#" Value="public interface IConfigurationManager&lt;T&gt; where T : class" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IConfigurationManager`1&lt;class T&gt;" />
  <TypeSignature Language="DocId" Value="T:Microsoft.IdentityModel.Protocols.IConfigurationManager`1" />
  <TypeSignature Language="VB.NET" Value="Public Interface IConfigurationManager(Of T)" />
  <TypeSignature Language="F#" Value="type IConfigurationManager&lt;'T (requires 'T : null)&gt; = interface" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.IdentityModel.Protocols</AssemblyName>
    <AssemblyVersion>2.1.3.0</AssemblyVersion>
    <AssemblyVersion>5.2.0.0</AssemblyVersion>
  </AssemblyInfo>
  <TypeParameters>
    <TypeParameter Name="T">
      <Constraints>
        <ParameterAttribute>ReferenceTypeConstraint</ParameterAttribute>
      </Constraints>
    </TypeParameter>
  </TypeParameters>
  <Interfaces />
  <Docs>
    <typeparam name="T"><span data-ttu-id="95cc5-101">Der <see cref="T:Microsoft.IdentityModel.Protocols.IDocumentRetriever" />-Typ.</span><span class="sxs-lookup"><span data-stu-id="95cc5-101">The type of <see cref="T:Microsoft.IdentityModel.Protocols.IDocumentRetriever" />.</span></span></typeparam>
    <summary>
            <span data-ttu-id="95cc5-102">Schnittstelle, die ein Modell zum Abrufen von Konfigurationsdaten definiert.</span><span class="sxs-lookup"><span data-stu-id="95cc5-102">Interface that defines a model for retrieving configuration data.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="GetConfigurationAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;T&gt; GetConfigurationAsync (System.Threading.CancellationToken cancel);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;!T&gt; GetConfigurationAsync(valuetype System.Threading.CancellationToken cancel) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.IdentityModel.Protocols.IConfigurationManager`1.GetConfigurationAsync(System.Threading.CancellationToken)" />
      <MemberSignature Language="VB.NET" Value="Public Function GetConfigurationAsync (cancel As CancellationToken) As Task(Of T)" />
      <MemberSignature Language="F#" Value="abstract member GetConfigurationAsync : System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;'T (requires 'T : null)&gt;" Usage="iConfigurationManager.GetConfigurationAsync cancel" />
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
        <Parameter Name="cancel" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="cancel">
          <see cref="T:System.Threading.CancellationToken" />
        </param>
        <summary>
            <span data-ttu-id="95cc5-103">Abrufen der aktuellen Konfigurations aktualisieren und/oder Zwischenspeichern nach Bedarf.</span><span class="sxs-lookup"><span data-stu-id="95cc5-103">Retrieve the current configuration, refreshing and/or caching as needed.</span></span>
            <span data-ttu-id="95cc5-104">Wenn die Konfiguration nicht abgerufen werden kann, statt Null zurückgegeben wird, ist diese Methode löst.</span><span class="sxs-lookup"><span data-stu-id="95cc5-104">This method will throw if the configuration cannot be retrieved, instead of returning null.</span></span>
            </summary>
        <returns>
          <see cref="T:System.Threading.Tasks.Task`1" />
        </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RequestRefresh">
      <MemberSignature Language="C#" Value="public void RequestRefresh ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void RequestRefresh() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.IdentityModel.Protocols.IConfigurationManager`1.RequestRefresh" />
      <MemberSignature Language="VB.NET" Value="Public Sub RequestRefresh ()" />
      <MemberSignature Language="F#" Value="abstract member RequestRefresh : unit -&gt; unit" Usage="iConfigurationManager.RequestRefresh " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.IdentityModel.Protocols</AssemblyName>
        <AssemblyVersion>2.1.3.0</AssemblyVersion>
        <AssemblyVersion>5.2.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="95cc5-105">Geben Sie an, dass die Konfiguration möglicherweise veraltete (wie durch wegen eines Fehlers beim Verarbeiten von eingehender Tokens angegeben).</span><span class="sxs-lookup"><span data-stu-id="95cc5-105">Indicate that the configuration may be stale (as indicated by failing to process incoming tokens).</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>