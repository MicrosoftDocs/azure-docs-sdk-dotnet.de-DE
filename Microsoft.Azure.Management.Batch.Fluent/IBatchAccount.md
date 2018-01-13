<Type Name="IBatchAccount" FullName="Microsoft.Azure.Management.Batch.Fluent.IBatchAccount">
  <TypeSignature Language="C#" Value="public interface IBatchAccount : Microsoft.Azure.Management.ResourceManager.Fluent.Core.IGroupableResource&lt;Microsoft.Azure.Management.Batch.Fluent.IBatchManager,Microsoft.Azure.Management.Batch.Fluent.Models.BatchAccountInner&gt;, Microsoft.Azure.Management.ResourceManager.Fluent.Core.IHasInner&lt;Microsoft.Azure.Management.Batch.Fluent.Models.BatchAccountInner&gt;, Microsoft.Azure.Management.ResourceManager.Fluent.Core.IHasManager&lt;Microsoft.Azure.Management.Batch.Fluent.IBatchManager&gt;, Microsoft.Azure.Management.ResourceManager.Fluent.Core.ResourceActions.IRefreshable&lt;Microsoft.Azure.Management.Batch.Fluent.IBatchAccount&gt;, Microsoft.Azure.Management.ResourceManager.Fluent.Core.ResourceActions.IUpdatable&lt;Microsoft.Azure.Management.Batch.Fluent.BatchAccount.Update.IUpdate&gt;" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IBatchAccount implements class Microsoft.Azure.Management.ResourceManager.Fluent.Core.IGroupableResource`2&lt;class Microsoft.Azure.Management.Batch.Fluent.IBatchManager, class Microsoft.Azure.Management.Batch.Fluent.Models.BatchAccountInner&gt;, class Microsoft.Azure.Management.ResourceManager.Fluent.Core.IHasId, class Microsoft.Azure.Management.ResourceManager.Fluent.Core.IHasInner`1&lt;class Microsoft.Azure.Management.Batch.Fluent.Models.BatchAccountInner&gt;, class Microsoft.Azure.Management.ResourceManager.Fluent.Core.IHasManager`1&lt;class Microsoft.Azure.Management.Batch.Fluent.IBatchManager&gt;, class Microsoft.Azure.Management.ResourceManager.Fluent.Core.IHasName, class Microsoft.Azure.Management.ResourceManager.Fluent.Core.IHasResourceGroup, class Microsoft.Azure.Management.ResourceManager.Fluent.Core.IResource, class Microsoft.Azure.Management.ResourceManager.Fluent.Core.ResourceActions.IIndexable, class Microsoft.Azure.Management.ResourceManager.Fluent.Core.ResourceActions.IRefreshable`1&lt;class Microsoft.Azure.Management.Batch.Fluent.IBatchAccount&gt;, class Microsoft.Azure.Management.ResourceManager.Fluent.Core.ResourceActions.IUpdatable`1&lt;class Microsoft.Azure.Management.Batch.Fluent.BatchAccount.Update.IUpdate&gt;" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Batch.Fluent.IBatchAccount" />
  <TypeSignature Language="VB.NET" Value="Public Interface IBatchAccount&#xA;Implements IGroupableResource(Of IBatchManager, BatchAccountInner), IHasInner(Of BatchAccountInner), IHasManager(Of IBatchManager), IRefreshable(Of IBatchAccount), IUpdatable(Of IUpdate)" />
  <TypeSignature Language="F#" Value="type IBatchAccount = interface&#xA;    interface IGroupableResource&lt;IBatchManager, BatchAccountInner&gt;&#xA;    interface IResource&#xA;    interface IIndexable&#xA;    interface IHasId&#xA;    interface IHasName&#xA;    interface IHasResourceGroup&#xA;    interface IHasManager&lt;IBatchManager&gt;&#xA;    interface IHasInner&lt;BatchAccountInner&gt;&#xA;    interface IRefreshable&lt;IBatchAccount&gt;&#xA;    interface IUpdatable&lt;IUpdate&gt;" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Batch.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces>
    <Interface>
      <InterfaceName>Microsoft.Azure.Management.ResourceManager.Fluent.Core.IGroupableResource&lt;Microsoft.Azure.Management.Batch.Fluent.IBatchManager,Microsoft.Azure.Management.Batch.Fluent.Models.BatchAccountInner&gt;</InterfaceName>
    </Interface>
    <Interface>
      <InterfaceName>Microsoft.Azure.Management.ResourceManager.Fluent.Core.IHasInner&lt;Microsoft.Azure.Management.Batch.Fluent.Models.BatchAccountInner&gt;</InterfaceName>
    </Interface>
    <Interface>
      <InterfaceName>Microsoft.Azure.Management.ResourceManager.Fluent.Core.IHasManager&lt;Microsoft.Azure.Management.Batch.Fluent.IBatchManager&gt;</InterfaceName>
    </Interface>
    <Interface>
      <InterfaceName>Microsoft.Azure.Management.ResourceManager.Fluent.Core.ResourceActions.IRefreshable&lt;Microsoft.Azure.Management.Batch.Fluent.IBatchAccount&gt;</InterfaceName>
    </Interface>
    <Interface>
      <InterfaceName>Microsoft.Azure.Management.ResourceManager.Fluent.Core.ResourceActions.IUpdatable&lt;Microsoft.Azure.Management.Batch.Fluent.BatchAccount.Update.IUpdate&gt;</InterfaceName>
    </Interface>
  </Interfaces>
  <Docs>
    <summary>
            <span data-ttu-id="d30b0-101">Eine unveränderliche clientseitige Darstellung eines Azure Batch-Kontos.</span><span class="sxs-lookup"><span data-stu-id="d30b0-101">An immutable client-side representation of an Azure Batch account.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="AccountEndpoint">
      <MemberSignature Language="C#" Value="public string AccountEndpoint { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string AccountEndpoint" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Batch.Fluent.IBatchAccount.AccountEndpoint" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property AccountEndpoint As String" />
      <MemberSignature Language="F#" Value="member this.AccountEndpoint : string" Usage="Microsoft.Azure.Management.Batch.Fluent.IBatchAccount.AccountEndpoint" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Batch.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="d30b0-102">Ruft die Batch-Endpunkt ab.</span><span class="sxs-lookup"><span data-stu-id="d30b0-102">Gets Batch account endpoint.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ActiveJobAndJobScheduleQuota">
      <MemberSignature Language="C#" Value="public int ActiveJobAndJobScheduleQuota { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int32 ActiveJobAndJobScheduleQuota" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Batch.Fluent.IBatchAccount.ActiveJobAndJobScheduleQuota" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ActiveJobAndJobScheduleQuota As Integer" />
      <MemberSignature Language="F#" Value="member this.ActiveJobAndJobScheduleQuota : int" Usage="Microsoft.Azure.Management.Batch.Fluent.IBatchAccount.ActiveJobAndJobScheduleQuota" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Batch.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Int32</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="d30b0-103">Ruft den aktiven Auftrag und den Auftrag-Zeitplan-Kontingent für dieses Batch-Konto ab.</span><span class="sxs-lookup"><span data-stu-id="d30b0-103">Gets the active job and job schedule quota for this Batch account.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Applications">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IReadOnlyDictionary&lt;string,Microsoft.Azure.Management.Batch.Fluent.IApplication&gt; Applications { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IReadOnlyDictionary`2&lt;string, class Microsoft.Azure.Management.Batch.Fluent.IApplication&gt; Applications" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Batch.Fluent.IBatchAccount.Applications" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Applications As IReadOnlyDictionary(Of String, IApplication)" />
      <MemberSignature Language="F#" Value="member this.Applications : System.Collections.Generic.IReadOnlyDictionary&lt;string, Microsoft.Azure.Management.Batch.Fluent.IApplication&gt;" Usage="Microsoft.Azure.Management.Batch.Fluent.IBatchAccount.Applications" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Batch.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IReadOnlyDictionary&lt;System.String,Microsoft.Azure.Management.Batch.Fluent.IApplication&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="d30b0-104">Anwendungen in diesem Batch-Konto, das nach Namen indiziert abgerufen.</span><span class="sxs-lookup"><span data-stu-id="d30b0-104">Gets applications in this Batch account, indexed by name.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AutoStorage">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Batch.Fluent.Models.AutoStorageProperties AutoStorage { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.Batch.Fluent.Models.AutoStorageProperties AutoStorage" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Batch.Fluent.IBatchAccount.AutoStorage" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property AutoStorage As AutoStorageProperties" />
      <MemberSignature Language="F#" Value="member this.AutoStorage : Microsoft.Azure.Management.Batch.Fluent.Models.AutoStorageProperties" Usage="Microsoft.Azure.Management.Batch.Fluent.IBatchAccount.AutoStorage" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Batch.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Batch.Fluent.Models.AutoStorageProperties</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="d30b0-105">Ruft die Eigenschaften und den Status des Auto-Speicherkonto, die dem Batch-Konto zugeordnet ist.</span><span class="sxs-lookup"><span data-stu-id="d30b0-105">Gets the properties and status of any auto storage account associated with the Batch account.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CoreQuota">
      <MemberSignature Language="C#" Value="public int CoreQuota { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int32 CoreQuota" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Batch.Fluent.IBatchAccount.CoreQuota" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property CoreQuota As Integer" />
      <MemberSignature Language="F#" Value="member this.CoreQuota : int" Usage="Microsoft.Azure.Management.Batch.Fluent.IBatchAccount.CoreQuota" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Batch.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Int32</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="d30b0-106">Ruft das kernnutzungskontingent für dieses Batch-Konto ab.</span><span class="sxs-lookup"><span data-stu-id="d30b0-106">Gets the core quota for this Batch account.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetKeys">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Batch.Fluent.BatchAccountKeys GetKeys ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Batch.Fluent.BatchAccountKeys GetKeys() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Batch.Fluent.IBatchAccount.GetKeys" />
      <MemberSignature Language="VB.NET" Value="Public Function GetKeys () As BatchAccountKeys" />
      <MemberSignature Language="F#" Value="abstract member GetKeys : unit -&gt; Microsoft.Azure.Management.Batch.Fluent.BatchAccountKeys" Usage="iBatchAccount.GetKeys " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Batch.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Batch.Fluent.BatchAccountKeys</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>To be added.</summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return><span data-ttu-id="d30b0-107">Der Zugriffsschlüssel für dieses Batch-Konto.</span><span class="sxs-lookup"><span data-stu-id="d30b0-107">The access keys for this Batch account.</span></span></return>
      </Docs>
    </Member>
    <Member MemberName="PoolQuota">
      <MemberSignature Language="C#" Value="public int PoolQuota { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int32 PoolQuota" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Batch.Fluent.IBatchAccount.PoolQuota" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property PoolQuota As Integer" />
      <MemberSignature Language="F#" Value="member this.PoolQuota : int" Usage="Microsoft.Azure.Management.Batch.Fluent.IBatchAccount.PoolQuota" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Batch.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Int32</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="d30b0-108">Ruft das poolkontingent für dieses Batch-Konto ab.</span><span class="sxs-lookup"><span data-stu-id="d30b0-108">Gets the pool quota for this Batch account.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ProvisioningState">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Batch.Fluent.Models.ProvisioningState ProvisioningState { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype Microsoft.Azure.Management.Batch.Fluent.Models.ProvisioningState ProvisioningState" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Batch.Fluent.IBatchAccount.ProvisioningState" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ProvisioningState As ProvisioningState" />
      <MemberSignature Language="F#" Value="member this.ProvisioningState : Microsoft.Azure.Management.Batch.Fluent.Models.ProvisioningState" Usage="Microsoft.Azure.Management.Batch.Fluent.IBatchAccount.ProvisioningState" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Batch.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Batch.Fluent.Models.ProvisioningState</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="d30b0-109">Ruft den Bereitstellungsstatus der Ressource ab.</span><span class="sxs-lookup"><span data-stu-id="d30b0-109">Gets the provisioned state of the resource.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RegenerateKeys">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Batch.Fluent.BatchAccountKeys RegenerateKeys (Microsoft.Azure.Management.Batch.Fluent.Models.AccountKeyType keyType);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Batch.Fluent.BatchAccountKeys RegenerateKeys(valuetype Microsoft.Azure.Management.Batch.Fluent.Models.AccountKeyType keyType) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Batch.Fluent.IBatchAccount.RegenerateKeys(Microsoft.Azure.Management.Batch.Fluent.Models.AccountKeyType)" />
      <MemberSignature Language="VB.NET" Value="Public Function RegenerateKeys (keyType As AccountKeyType) As BatchAccountKeys" />
      <MemberSignature Language="F#" Value="abstract member RegenerateKeys : Microsoft.Azure.Management.Batch.Fluent.Models.AccountKeyType -&gt; Microsoft.Azure.Management.Batch.Fluent.BatchAccountKeys" Usage="iBatchAccount.RegenerateKeys keyType" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Batch.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Batch.Fluent.BatchAccountKeys</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="keyType" Type="Microsoft.Azure.Management.Batch.Fluent.Models.AccountKeyType" />
      </Parameters>
      <Docs>
        <param name="keyType"><span data-ttu-id="d30b0-110">Der Typ, wenn der Schlüssel erneut generieren.</span><span class="sxs-lookup"><span data-stu-id="d30b0-110">The type if key to regenerate.</span></span></param>
        <summary>
            <span data-ttu-id="d30b0-111">Generiert die Zugriffsschlüssel für Batch-Konto an.</span><span class="sxs-lookup"><span data-stu-id="d30b0-111">Regenerates the access keys for the Batch account.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return><span data-ttu-id="d30b0-112">Zugriffsschlüssel für dieses Batch-Konto neu generiert.</span><span class="sxs-lookup"><span data-stu-id="d30b0-112">Regenerated access keys for this Batch account.</span></span></return>
      </Docs>
    </Member>
    <Member MemberName="SynchronizeAutoStorageKeys">
      <MemberSignature Language="C#" Value="public void SynchronizeAutoStorageKeys ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void SynchronizeAutoStorageKeys() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Batch.Fluent.IBatchAccount.SynchronizeAutoStorageKeys" />
      <MemberSignature Language="VB.NET" Value="Public Sub SynchronizeAutoStorageKeys ()" />
      <MemberSignature Language="F#" Value="abstract member SynchronizeAutoStorageKeys : unit -&gt; unit" Usage="iBatchAccount.SynchronizeAutoStorageKeys " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Batch.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="d30b0-113">Synchronisiert die speicherkontoschlüssel für dieses Batch-Konto an.</span><span class="sxs-lookup"><span data-stu-id="d30b0-113">Synchronizes the storage account keys for this Batch account.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>