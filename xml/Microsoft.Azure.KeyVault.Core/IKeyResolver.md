<Type Name="IKeyResolver" FullName="Microsoft.Azure.KeyVault.Core.IKeyResolver">
  <TypeSignature Language="C#" Value="public interface IKeyResolver" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IKeyResolver" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.KeyVault.Core.IKeyResolver" />
  <TypeSignature Language="VB.NET" Value="Public Interface IKeyResolver" />
  <TypeSignature Language="F#" Value="type IKeyResolver = interface" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.KeyVault.Core</AssemblyName>
    <AssemblyVersion>2.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="691e7-101">Eine Schnittstelle für wichtige Konfliktlöser.</span><span class="sxs-lookup"><span data-stu-id="691e7-101">Interface for key resolvers.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="ResolveKeyAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.KeyVault.Core.IKey&gt; ResolveKeyAsync (string kid, System.Threading.CancellationToken token);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.KeyVault.Core.IKey&gt; ResolveKeyAsync(string kid, valuetype System.Threading.CancellationToken token) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.KeyVault.Core.IKeyResolver.ResolveKeyAsync(System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="VB.NET" Value="Public Function ResolveKeyAsync (kid As String, token As CancellationToken) As Task(Of IKey)" />
      <MemberSignature Language="F#" Value="abstract member ResolveKeyAsync : string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.KeyVault.Core.IKey&gt;" Usage="iKeyResolver.ResolveKeyAsync (kid, token)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault.Core</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.KeyVault.Core.IKey&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="kid" Type="System.String" />
        <Parameter Name="token" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="kid"><span data-ttu-id="691e7-102">Der Schlüsselbezeichner aufgelöst</span><span class="sxs-lookup"><span data-stu-id="691e7-102">The key identifier to resolve</span></span></param>
        <param name="token"><span data-ttu-id="691e7-103">Abbruchtoken</span><span class="sxs-lookup"><span data-stu-id="691e7-103">Cancellation token</span></span></param>
        <summary>
            <span data-ttu-id="691e7-104">Stellt eine Implementierung IKey für den angegebenen Schlüsselbezeichner.</span><span class="sxs-lookup"><span data-stu-id="691e7-104">Provides an IKey implementation for the specified key identifier.</span></span>
            </summary>
        <returns><span data-ttu-id="691e7-105">Der aufgelöste IKey Implementierung oder null</span><span class="sxs-lookup"><span data-stu-id="691e7-105">The resolved IKey implementation or null</span></span></returns>
        <remarks><span data-ttu-id="691e7-106">Implementierungen sollten überprüfen, das Format "Kid", um sicherzustellen, dass er erkannt wird.</span><span class="sxs-lookup"><span data-stu-id="691e7-106">Implementations should check the format of the kid to ensure that it is recognized.</span></span> <span data-ttu-id="691e7-107">NULL, anstatt eine Ausnahme sollte für unbekannte Schlüsselbezeichner zum Aktivieren der Verkettung der wichtigsten Konfliktlöser zurückgegeben werden.</span><span class="sxs-lookup"><span data-stu-id="691e7-107">Null, rather than an exception, should be returned for unrecognized key identifiers to enable chaining of key resolvers.</span></span></remarks>
      </Docs>
    </Member>
  </Members>
</Type>