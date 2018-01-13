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
            Eine unveränderliche clientseitige Darstellung einer Zugriffsrichtlinie für den schlüsseltresor.
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
        <value>Anwendungs-ID des Clients durchführen der Anforderung im Auftrag eines Prinzipals.</value>
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
        <value>Die Objekt-ID eines Benutzers oder eines dienstprinzipals in Azure Active</value>
        <value>Directory-Mandanten für den Tresor.</value>
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
        <value>Über Berechtigungen verfügt die Identität für den Schlüssel und geheimen Bereiche.</value>
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
        <value>Die Azure Active Directory-Mandanten-ID, die verwendet werden soll</value>
        <value>Authentifizieren von Anforderungen für den schlüsseltresor.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>