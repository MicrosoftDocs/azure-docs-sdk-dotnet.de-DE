<Type Name="IProviders" FullName="Microsoft.Azure.Management.ResourceManager.Fluent.IProviders">
  <TypeSignature Language="C#" Value="public interface IProviders : Microsoft.Azure.Management.ResourceManager.Fluent.Core.CollectionActions.ISupportsGettingByName&lt;Microsoft.Azure.Management.ResourceManager.Fluent.IProvider&gt;, Microsoft.Azure.Management.ResourceManager.Fluent.Core.CollectionActions.ISupportsListing&lt;Microsoft.Azure.Management.ResourceManager.Fluent.IProvider&gt;" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IProviders implements class Microsoft.Azure.Management.ResourceManager.Fluent.Core.CollectionActions.ISupportsGettingByName`1&lt;class Microsoft.Azure.Management.ResourceManager.Fluent.IProvider&gt;, class Microsoft.Azure.Management.ResourceManager.Fluent.Core.CollectionActions.ISupportsListing`1&lt;class Microsoft.Azure.Management.ResourceManager.Fluent.IProvider&gt;" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.ResourceManager.Fluent.IProviders" />
  <TypeSignature Language="VB.NET" Value="Public Interface IProviders&#xA;Implements ISupportsGettingByName(Of IProvider), ISupportsListing(Of IProvider)" />
  <TypeSignature Language="F#" Value="type IProviders = interface&#xA;    interface ISupportsListing&lt;IProvider&gt;&#xA;    interface ISupportsGettingByName&lt;IProvider&gt;" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.ResourceManager.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces>
    <Interface>
      <InterfaceName>Microsoft.Azure.Management.ResourceManager.Fluent.Core.CollectionActions.ISupportsGettingByName&lt;Microsoft.Azure.Management.ResourceManager.Fluent.IProvider&gt;</InterfaceName>
    </Interface>
    <Interface>
      <InterfaceName>Microsoft.Azure.Management.ResourceManager.Fluent.Core.CollectionActions.ISupportsListing&lt;Microsoft.Azure.Management.ResourceManager.Fluent.IProvider&gt;</InterfaceName>
    </Interface>
  </Interfaces>
  <Docs>
    <summary>
            <span data-ttu-id="0572f-101">Einstiegspunkt für Anbieter-API.</span><span class="sxs-lookup"><span data-stu-id="0572f-101">Entry point to providers management API.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="Register">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.ResourceManager.Fluent.IProvider Register (string resourceProviderNamespace);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.ResourceManager.Fluent.IProvider Register(string resourceProviderNamespace) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ResourceManager.Fluent.IProviders.Register(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function Register (resourceProviderNamespace As String) As IProvider" />
      <MemberSignature Language="F#" Value="abstract member Register : string -&gt; Microsoft.Azure.Management.ResourceManager.Fluent.IProvider" Usage="iProviders.Register resourceProviderNamespace" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.ResourceManager.Fluent.IProvider</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceProviderNamespace" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="resourceProviderNamespace"><span data-ttu-id="0572f-102">ResourceProviderNamespace Namespace des Ressourcenanbieters.</span><span class="sxs-lookup"><span data-stu-id="0572f-102">resourceProviderNamespace Namespace of the resource provider</span></span></param>
        <summary>
            <span data-ttu-id="0572f-103">Register-Anbieter mit einem Abonnement verwendet werden soll.</span><span class="sxs-lookup"><span data-stu-id="0572f-103">Registers provider to be used with a subscription.</span></span>
            </summary>
        <returns><span data-ttu-id="0572f-104">Das ProviderInner-Objekt umschlossen {@link ServiceResponse} im Erfolgsfall</span><span class="sxs-lookup"><span data-stu-id="0572f-104">the ProviderInner object wrapped in {@link ServiceResponse} if successful</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RegisterAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.ResourceManager.Fluent.IProvider&gt; RegisterAsync (string resourceProviderNamespace, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.ResourceManager.Fluent.IProvider&gt; RegisterAsync(string resourceProviderNamespace, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ResourceManager.Fluent.IProviders.RegisterAsync(System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member RegisterAsync : string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.ResourceManager.Fluent.IProvider&gt;" Usage="iProviders.RegisterAsync (resourceProviderNamespace, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.ResourceManager.Fluent.IProvider&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceProviderNamespace" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceProviderNamespace"><span data-ttu-id="0572f-105">ResourceProviderNamespace Namespace des Ressourcenanbieters.</span><span class="sxs-lookup"><span data-stu-id="0572f-105">resourceProviderNamespace Namespace of the resource provider</span></span></param>
        <param name="cancellationToken">To be added.</param>
        <summary>
            <span data-ttu-id="0572f-106">Register-Anbieter mit einem Abonnement verwendet werden soll.</span><span class="sxs-lookup"><span data-stu-id="0572f-106">Registers provider to be used with a subscription.</span></span>
            </summary>
        <returns><span data-ttu-id="0572f-107">Das ProviderInner-Objekt umschlossen {@link ServiceResponse} im Erfolgsfall</span><span class="sxs-lookup"><span data-stu-id="0572f-107">the ProviderInner object wrapped in {@link ServiceResponse} if successful</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Unregister">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.ResourceManager.Fluent.IProvider Unregister (string resourceProviderNamespace);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.ResourceManager.Fluent.IProvider Unregister(string resourceProviderNamespace) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ResourceManager.Fluent.IProviders.Unregister(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function Unregister (resourceProviderNamespace As String) As IProvider" />
      <MemberSignature Language="F#" Value="abstract member Unregister : string -&gt; Microsoft.Azure.Management.ResourceManager.Fluent.IProvider" Usage="iProviders.Unregister resourceProviderNamespace" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.ResourceManager.Fluent.IProvider</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceProviderNamespace" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="resourceProviderNamespace"><span data-ttu-id="0572f-108">ResourceProviderNamespace Namespace des Ressourcenanbieters.</span><span class="sxs-lookup"><span data-stu-id="0572f-108">resourceProviderNamespace Namespace of the resource provider</span></span></param>
        <summary>
            <span data-ttu-id="0572f-109">Hebt die Registrierung Anbieter aus einem Abonnement.</span><span class="sxs-lookup"><span data-stu-id="0572f-109">Unregisters provider from a subscription.</span></span>
            </summary>
        <returns><span data-ttu-id="0572f-110">Das ProviderInner-Objekt umschlossen {@link ServiceResponse} im Erfolgsfall</span><span class="sxs-lookup"><span data-stu-id="0572f-110">the ProviderInner object wrapped in {@link ServiceResponse} if successful</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UnregisterAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.ResourceManager.Fluent.IProvider&gt; UnregisterAsync (string resourceProviderNamespace, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.ResourceManager.Fluent.IProvider&gt; UnregisterAsync(string resourceProviderNamespace, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ResourceManager.Fluent.IProviders.UnregisterAsync(System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member UnregisterAsync : string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.ResourceManager.Fluent.IProvider&gt;" Usage="iProviders.UnregisterAsync (resourceProviderNamespace, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.ResourceManager.Fluent.IProvider&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceProviderNamespace" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceProviderNamespace"><span data-ttu-id="0572f-111">ResourceProviderNamespace Namespace des Ressourcenanbieters.</span><span class="sxs-lookup"><span data-stu-id="0572f-111">resourceProviderNamespace Namespace of the resource provider</span></span></param>
        <param name="cancellationToken">To be added.</param>
        <summary>
            <span data-ttu-id="0572f-112">Hebt die Registrierung Anbieter aus einem Abonnement.</span><span class="sxs-lookup"><span data-stu-id="0572f-112">Unregisters provider from a subscription.</span></span>
            </summary>
        <returns><span data-ttu-id="0572f-113">Das ProviderInner-Objekt umschlossen {@link ServiceResponse} im Erfolgsfall</span><span class="sxs-lookup"><span data-stu-id="0572f-113">the ProviderInner object wrapped in {@link ServiceResponse} if successful</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>