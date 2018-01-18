<Type Name="IAccessPolicy" FullName="Microsoft.Azure.Management.KeyVault.Fluent.IAccessPolicy">
  <TypeSignature Language="C#" Value="public interface IAccessPolicy : Microsoft.Azure.Management.ResourceManager.Fluent.Core.IChildResource&lt;Microsoft.Azure.Management.KeyVault.Fluent.IVault&gt;, Microsoft.Azure.Management.ResourceManager.Fluent.Core.IHasInner&lt;Microsoft.Azure.Management.KeyVault.Fluent.Models.AccessPolicyEntry&gt;, Microsoft.Azure.Management.ResourceManager.Fluent.Core.IHasParent&lt;Microsoft.Azure.Management.KeyVault.Fluent.IVault&gt;" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IAccessPolicy implements class Microsoft.Azure.Management.ResourceManager.Fluent.Core.IChildResource`1&lt;class Microsoft.Azure.Management.KeyVault.Fluent.IVault&gt;, class Microsoft.Azure.Management.ResourceManager.Fluent.Core.IHasInner`1&lt;class Microsoft.Azure.Management.KeyVault.Fluent.Models.AccessPolicyEntry&gt;, class Microsoft.Azure.Management.ResourceManager.Fluent.Core.IHasName, class Microsoft.Azure.Management.ResourceManager.Fluent.Core.IHasParent`1&lt;class Microsoft.Azure.Management.KeyVault.Fluent.IVault&gt;, class Microsoft.Azure.Management.ResourceManager.Fluent.Core.ResourceActions.IIndexable" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.KeyVault.Fluent.IAccessPolicy" />
  <TypeSignature Language="VB.NET" Value="Public Interface IAccessPolicy&#xA;Implements IChildResource(Of IVault), IHasInner(Of AccessPolicyEntry), IHasParent(Of IVault)" />
  <TypeSignature Language="F#" Value="type IAccessPolicy = interface&#xA;    interface IChildResource&lt;IVault&gt;&#xA;    interface IHasName&#xA;    interface IIndexable&#xA;    interface IHasParent&lt;IVault&gt;&#xA;    interface IHasInner&lt;AccessPolicyEntry&gt;" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.KeyVault.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces>
    <Interface>
      <InterfaceName>Microsoft.Azure.Management.ResourceManager.Fluent.Core.IChildResource&lt;Microsoft.Azure.Management.KeyVault.Fluent.IVault&gt;</InterfaceName>
    </Interface>
    <Interface>
      <InterfaceName>Microsoft.Azure.Management.ResourceManager.Fluent.Core.IHasInner&lt;Microsoft.Azure.Management.KeyVault.Fluent.Models.AccessPolicyEntry&gt;</InterfaceName>
    </Interface>
    <Interface>
      <InterfaceName>Microsoft.Azure.Management.ResourceManager.Fluent.Core.IHasParent&lt;Microsoft.Azure.Management.KeyVault.Fluent.IVault&gt;</InterfaceName>
    </Interface>
  </Interfaces>
  <Docs>
    <summary>
            <span data-ttu-id="0933a-101">Eine unveränderliche clientseitige Darstellung einer Zugriffsrichtlinie für den schlüsseltresor.</span><span class="sxs-lookup"><span data-stu-id="0933a-101">An immutable client-side representation of a key vault access policy.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="ApplicationId">
      <MemberSignature Language="C#" Value="public string ApplicationId { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ApplicationId" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.KeyVault.Fluent.IAccessPolicy.ApplicationId" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ApplicationId As String" />
      <MemberSignature Language="F#" Value="member this.ApplicationId : string" Usage="Microsoft.Azure.Management.KeyVault.Fluent.IAccessPolicy.ApplicationId" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.KeyVault.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>To be added.</summary>
        <value><span data-ttu-id="0933a-102">Anwendungs-ID des Clients durchführen der Anforderung im Auftrag eines Prinzipals.</span><span class="sxs-lookup"><span data-stu-id="0933a-102">Application ID of the client making request on behalf of a principal.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ObjectId">
      <MemberSignature Language="C#" Value="public string ObjectId { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ObjectId" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.KeyVault.Fluent.IAccessPolicy.ObjectId" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ObjectId As String" />
      <MemberSignature Language="F#" Value="member this.ObjectId : string" Usage="Microsoft.Azure.Management.KeyVault.Fluent.IAccessPolicy.ObjectId" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.KeyVault.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>To be added.</summary>
        <value><span data-ttu-id="0933a-103">Die Objekt-ID eines Benutzers oder eines dienstprinzipals in Azure Active</span><span class="sxs-lookup"><span data-stu-id="0933a-103">The object ID of a user or service principal in the Azure Active</span></span></value>
        <value><span data-ttu-id="0933a-104">Directory-Mandanten für den Tresor.</span><span class="sxs-lookup"><span data-stu-id="0933a-104">Directory tenant for the vault.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Permissions">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.KeyVault.Fluent.Models.Permissions Permissions { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.KeyVault.Fluent.Models.Permissions Permissions" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.KeyVault.Fluent.IAccessPolicy.Permissions" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Permissions As Permissions" />
      <MemberSignature Language="F#" Value="member this.Permissions : Microsoft.Azure.Management.KeyVault.Fluent.Models.Permissions" Usage="Microsoft.Azure.Management.KeyVault.Fluent.IAccessPolicy.Permissions" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.KeyVault.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.KeyVault.Fluent.Models.Permissions</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>To be added.</summary>
        <value><span data-ttu-id="0933a-105">Über Berechtigungen verfügt die Identität für den Schlüssel und geheimen Bereiche.</span><span class="sxs-lookup"><span data-stu-id="0933a-105">Permissions the identity has for keys and secrets.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="TenantId">
      <MemberSignature Language="C#" Value="public string TenantId { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string TenantId" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.KeyVault.Fluent.IAccessPolicy.TenantId" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property TenantId As String" />
      <MemberSignature Language="F#" Value="member this.TenantId : string" Usage="Microsoft.Azure.Management.KeyVault.Fluent.IAccessPolicy.TenantId" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.KeyVault.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>To be added.</summary>
        <value><span data-ttu-id="0933a-106">Die Azure Active Directory-Mandanten-ID, die verwendet werden soll</span><span class="sxs-lookup"><span data-stu-id="0933a-106">The Azure Active Directory tenant ID that should be used for</span></span></value>
        <value><span data-ttu-id="0933a-107">Authentifizieren von Anforderungen für den schlüsseltresor.</span><span class="sxs-lookup"><span data-stu-id="0933a-107">authenticating requests to the key vault.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>