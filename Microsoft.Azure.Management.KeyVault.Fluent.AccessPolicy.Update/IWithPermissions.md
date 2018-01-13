<Type Name="IWithPermissions" FullName="Microsoft.Azure.Management.KeyVault.Fluent.AccessPolicy.Update.IWithPermissions">
  <TypeSignature Language="C#" Value="public interface IWithPermissions" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IWithPermissions" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.KeyVault.Fluent.AccessPolicy.Update.IWithPermissions" />
  <TypeSignature Language="VB.NET" Value="Public Interface IWithPermissions" />
  <TypeSignature Language="F#" Value="type IWithPermissions = interface" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.KeyVault.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="4f1a0-101">Die Zugriffsrichtlinie aktualisieren Stufe ermöglicht Berechtigungen hinzugefügt oder entfernt werden soll.</span><span class="sxs-lookup"><span data-stu-id="4f1a0-101">The access policy update stage allowing permissions to be added or removed.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="AllowKeyAllPermissions">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.KeyVault.Fluent.AccessPolicy.Update.IUpdate AllowKeyAllPermissions ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.KeyVault.Fluent.AccessPolicy.Update.IUpdate AllowKeyAllPermissions() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.KeyVault.Fluent.AccessPolicy.Update.IWithPermissions.AllowKeyAllPermissions" />
      <MemberSignature Language="VB.NET" Value="Public Function AllowKeyAllPermissions () As IUpdate" />
      <MemberSignature Language="F#" Value="abstract member AllowKeyAllPermissions : unit -&gt; Microsoft.Azure.Management.KeyVault.Fluent.AccessPolicy.Update.IUpdate" Usage="iWithPermissions.AllowKeyAllPermissions " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.KeyVault.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.KeyVault.Fluent.AccessPolicy.Update.IUpdate</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="4f1a0-102">Ermöglichen Sie alle Berechtigungen für die AD-Identität zu Zugriffstasten.</span><span class="sxs-lookup"><span data-stu-id="4f1a0-102">Allow all permissions for the AD identity to access keys.</span></span>
            </summary>
        <returns><span data-ttu-id="4f1a0-103">die nächste Phase der Access-richtlinienaktualisierung</span><span class="sxs-lookup"><span data-stu-id="4f1a0-103">the next stage of access policy update</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AllowKeyPermissions">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.KeyVault.Fluent.AccessPolicy.Update.IUpdate AllowKeyPermissions (params Microsoft.Azure.Management.KeyVault.Fluent.Models.KeyPermissions[] permissions);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.KeyVault.Fluent.AccessPolicy.Update.IUpdate AllowKeyPermissions(class Microsoft.Azure.Management.KeyVault.Fluent.Models.KeyPermissions[] permissions) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.KeyVault.Fluent.AccessPolicy.Update.IWithPermissions.AllowKeyPermissions(Microsoft.Azure.Management.KeyVault.Fluent.Models.KeyPermissions[])" />
      <MemberSignature Language="VB.NET" Value="Public Function AllowKeyPermissions (ParamArray permissions As KeyPermissions()) As IUpdate" />
      <MemberSignature Language="F#" Value="abstract member AllowKeyPermissions : Microsoft.Azure.Management.KeyVault.Fluent.Models.KeyPermissions[] -&gt; Microsoft.Azure.Management.KeyVault.Fluent.AccessPolicy.Update.IUpdate" Usage="iWithPermissions.AllowKeyPermissions permissions" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.KeyVault.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.KeyVault.Fluent.AccessPolicy.Update.IUpdate</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="permissions" Type="Microsoft.Azure.Management.KeyVault.Fluent.Models.KeyPermissions[]">
          <Attributes>
            <Attribute>
              <AttributeName>System.ParamArray</AttributeName>
            </Attribute>
          </Attributes>
        </Parameter>
      </Parameters>
      <Docs>
        <param name="permissions"><span data-ttu-id="4f1a0-104">Berechtigungen, die die Liste der Berechtigungen gewährt.</span><span class="sxs-lookup"><span data-stu-id="4f1a0-104">permissions the list of permissions allowed</span></span></param>
        <summary>
            <span data-ttu-id="4f1a0-105">Lassen Sie eine Liste der Berechtigungen für die AD-Identität zu Zugriffstasten.</span><span class="sxs-lookup"><span data-stu-id="4f1a0-105">Allow a list of permissions for the AD identity to access keys.</span></span>
            </summary>
        <returns><span data-ttu-id="4f1a0-106">die nächste Phase der Access-richtlinienaktualisierung</span><span class="sxs-lookup"><span data-stu-id="4f1a0-106">the next stage of access policy update</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AllowKeyPermissions">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.KeyVault.Fluent.AccessPolicy.Update.IUpdate AllowKeyPermissions (System.Collections.Generic.IList&lt;Microsoft.Azure.Management.KeyVault.Fluent.Models.KeyPermissions&gt; permissions);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.KeyVault.Fluent.AccessPolicy.Update.IUpdate AllowKeyPermissions(class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.KeyVault.Fluent.Models.KeyPermissions&gt; permissions) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.KeyVault.Fluent.AccessPolicy.Update.IWithPermissions.AllowKeyPermissions(System.Collections.Generic.IList{Microsoft.Azure.Management.KeyVault.Fluent.Models.KeyPermissions})" />
      <MemberSignature Language="VB.NET" Value="Public Function AllowKeyPermissions (permissions As IList(Of KeyPermissions)) As IUpdate" />
      <MemberSignature Language="F#" Value="abstract member AllowKeyPermissions : System.Collections.Generic.IList&lt;Microsoft.Azure.Management.KeyVault.Fluent.Models.KeyPermissions&gt; -&gt; Microsoft.Azure.Management.KeyVault.Fluent.AccessPolicy.Update.IUpdate" Usage="iWithPermissions.AllowKeyPermissions permissions" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.KeyVault.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.KeyVault.Fluent.AccessPolicy.Update.IUpdate</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="permissions" Type="System.Collections.Generic.IList&lt;Microsoft.Azure.Management.KeyVault.Fluent.Models.KeyPermissions&gt;" />
      </Parameters>
      <Docs>
        <param name="permissions"><span data-ttu-id="4f1a0-107">Berechtigungen, die die Liste der Berechtigungen gewährt.</span><span class="sxs-lookup"><span data-stu-id="4f1a0-107">permissions the list of permissions allowed</span></span></param>
        <summary>
            <span data-ttu-id="4f1a0-108">Lassen Sie eine Liste der Berechtigungen für die AD-Identität zu Zugriffstasten.</span><span class="sxs-lookup"><span data-stu-id="4f1a0-108">Allow a list of permissions for the AD identity to access keys.</span></span>
            </summary>
        <returns><span data-ttu-id="4f1a0-109">die nächste Phase der Access-richtlinienaktualisierung</span><span class="sxs-lookup"><span data-stu-id="4f1a0-109">the next stage of access policy update</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AllowSecretAllPermissions">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.KeyVault.Fluent.AccessPolicy.Update.IUpdate AllowSecretAllPermissions ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.KeyVault.Fluent.AccessPolicy.Update.IUpdate AllowSecretAllPermissions() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.KeyVault.Fluent.AccessPolicy.Update.IWithPermissions.AllowSecretAllPermissions" />
      <MemberSignature Language="VB.NET" Value="Public Function AllowSecretAllPermissions () As IUpdate" />
      <MemberSignature Language="F#" Value="abstract member AllowSecretAllPermissions : unit -&gt; Microsoft.Azure.Management.KeyVault.Fluent.AccessPolicy.Update.IUpdate" Usage="iWithPermissions.AllowSecretAllPermissions " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.KeyVault.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.KeyVault.Fluent.AccessPolicy.Update.IUpdate</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="4f1a0-110">Ermöglichen Sie alle Berechtigungen für die AD-Identität auf geheime Schlüssel zugreifen.</span><span class="sxs-lookup"><span data-stu-id="4f1a0-110">Allow all permissions for the AD identity to access secrets.</span></span>
            </summary>
        <returns><span data-ttu-id="4f1a0-111">die nächste Phase der Richtliniendefinition Zugriff</span><span class="sxs-lookup"><span data-stu-id="4f1a0-111">the next stage of access policy definition</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AllowSecretPermissions">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.KeyVault.Fluent.AccessPolicy.Update.IUpdate AllowSecretPermissions (params Microsoft.Azure.Management.KeyVault.Fluent.Models.SecretPermissions[] permissions);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.KeyVault.Fluent.AccessPolicy.Update.IUpdate AllowSecretPermissions(class Microsoft.Azure.Management.KeyVault.Fluent.Models.SecretPermissions[] permissions) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.KeyVault.Fluent.AccessPolicy.Update.IWithPermissions.AllowSecretPermissions(Microsoft.Azure.Management.KeyVault.Fluent.Models.SecretPermissions[])" />
      <MemberSignature Language="VB.NET" Value="Public Function AllowSecretPermissions (ParamArray permissions As SecretPermissions()) As IUpdate" />
      <MemberSignature Language="F#" Value="abstract member AllowSecretPermissions : Microsoft.Azure.Management.KeyVault.Fluent.Models.SecretPermissions[] -&gt; Microsoft.Azure.Management.KeyVault.Fluent.AccessPolicy.Update.IUpdate" Usage="iWithPermissions.AllowSecretPermissions permissions" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.KeyVault.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.KeyVault.Fluent.AccessPolicy.Update.IUpdate</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="permissions" Type="Microsoft.Azure.Management.KeyVault.Fluent.Models.SecretPermissions[]">
          <Attributes>
            <Attribute>
              <AttributeName>System.ParamArray</AttributeName>
            </Attribute>
          </Attributes>
        </Parameter>
      </Parameters>
      <Docs>
        <param name="permissions"><span data-ttu-id="4f1a0-112">Berechtigungen, die die Liste der Berechtigungen gewährt.</span><span class="sxs-lookup"><span data-stu-id="4f1a0-112">permissions the list of permissions allowed</span></span></param>
        <summary>
            <span data-ttu-id="4f1a0-113">Lassen Sie eine Liste der Berechtigungen für die AD-Identität geheime Schlüssel zugreifen.</span><span class="sxs-lookup"><span data-stu-id="4f1a0-113">Allow a list of permissions for the AD identity to access secrets.</span></span>
            </summary>
        <returns><span data-ttu-id="4f1a0-114">die nächste Phase der Richtliniendefinition Zugriff</span><span class="sxs-lookup"><span data-stu-id="4f1a0-114">the next stage of access policy definition</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AllowSecretPermissions">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.KeyVault.Fluent.AccessPolicy.Update.IUpdate AllowSecretPermissions (System.Collections.Generic.IList&lt;Microsoft.Azure.Management.KeyVault.Fluent.Models.SecretPermissions&gt; permissions);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.KeyVault.Fluent.AccessPolicy.Update.IUpdate AllowSecretPermissions(class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.KeyVault.Fluent.Models.SecretPermissions&gt; permissions) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.KeyVault.Fluent.AccessPolicy.Update.IWithPermissions.AllowSecretPermissions(System.Collections.Generic.IList{Microsoft.Azure.Management.KeyVault.Fluent.Models.SecretPermissions})" />
      <MemberSignature Language="VB.NET" Value="Public Function AllowSecretPermissions (permissions As IList(Of SecretPermissions)) As IUpdate" />
      <MemberSignature Language="F#" Value="abstract member AllowSecretPermissions : System.Collections.Generic.IList&lt;Microsoft.Azure.Management.KeyVault.Fluent.Models.SecretPermissions&gt; -&gt; Microsoft.Azure.Management.KeyVault.Fluent.AccessPolicy.Update.IUpdate" Usage="iWithPermissions.AllowSecretPermissions permissions" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.KeyVault.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.KeyVault.Fluent.AccessPolicy.Update.IUpdate</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="permissions" Type="System.Collections.Generic.IList&lt;Microsoft.Azure.Management.KeyVault.Fluent.Models.SecretPermissions&gt;" />
      </Parameters>
      <Docs>
        <param name="permissions"><span data-ttu-id="4f1a0-115">Berechtigungen, die die Liste der Berechtigungen gewährt.</span><span class="sxs-lookup"><span data-stu-id="4f1a0-115">permissions the list of permissions allowed</span></span></param>
        <summary>
            <span data-ttu-id="4f1a0-116">Lassen Sie eine Liste der Berechtigungen für die AD-Identität geheime Schlüssel zugreifen.</span><span class="sxs-lookup"><span data-stu-id="4f1a0-116">Allow a list of permissions for the AD identity to access secrets.</span></span>
            </summary>
        <returns><span data-ttu-id="4f1a0-117">die nächste Phase der Richtliniendefinition Zugriff</span><span class="sxs-lookup"><span data-stu-id="4f1a0-117">the next stage of access policy definition</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DisallowKeyAllPermissions">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.KeyVault.Fluent.AccessPolicy.Update.IUpdate DisallowKeyAllPermissions ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.KeyVault.Fluent.AccessPolicy.Update.IUpdate DisallowKeyAllPermissions() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.KeyVault.Fluent.AccessPolicy.Update.IWithPermissions.DisallowKeyAllPermissions" />
      <MemberSignature Language="VB.NET" Value="Public Function DisallowKeyAllPermissions () As IUpdate" />
      <MemberSignature Language="F#" Value="abstract member DisallowKeyAllPermissions : unit -&gt; Microsoft.Azure.Management.KeyVault.Fluent.AccessPolicy.Update.IUpdate" Usage="iWithPermissions.DisallowKeyAllPermissions " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.KeyVault.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.KeyVault.Fluent.AccessPolicy.Update.IUpdate</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="4f1a0-118">Heben Sie alle Berechtigungen für die AD-Identität zu Zugriffstasten.</span><span class="sxs-lookup"><span data-stu-id="4f1a0-118">Revoke all permissions for the AD identity to access keys.</span></span>
            </summary>
        <returns><span data-ttu-id="4f1a0-119">die nächste Phase der Access-richtlinienaktualisierung</span><span class="sxs-lookup"><span data-stu-id="4f1a0-119">the next stage of access policy update</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DisallowKeyPermissions">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.KeyVault.Fluent.AccessPolicy.Update.IUpdate DisallowKeyPermissions (params Microsoft.Azure.Management.KeyVault.Fluent.Models.KeyPermissions[] permissions);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.KeyVault.Fluent.AccessPolicy.Update.IUpdate DisallowKeyPermissions(class Microsoft.Azure.Management.KeyVault.Fluent.Models.KeyPermissions[] permissions) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.KeyVault.Fluent.AccessPolicy.Update.IWithPermissions.DisallowKeyPermissions(Microsoft.Azure.Management.KeyVault.Fluent.Models.KeyPermissions[])" />
      <MemberSignature Language="VB.NET" Value="Public Function DisallowKeyPermissions (ParamArray permissions As KeyPermissions()) As IUpdate" />
      <MemberSignature Language="F#" Value="abstract member DisallowKeyPermissions : Microsoft.Azure.Management.KeyVault.Fluent.Models.KeyPermissions[] -&gt; Microsoft.Azure.Management.KeyVault.Fluent.AccessPolicy.Update.IUpdate" Usage="iWithPermissions.DisallowKeyPermissions permissions" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.KeyVault.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.KeyVault.Fluent.AccessPolicy.Update.IUpdate</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="permissions" Type="Microsoft.Azure.Management.KeyVault.Fluent.Models.KeyPermissions[]">
          <Attributes>
            <Attribute>
              <AttributeName>System.ParamArray</AttributeName>
            </Attribute>
          </Attributes>
        </Parameter>
      </Parameters>
      <Docs>
        <param name="permissions"><span data-ttu-id="4f1a0-120">Berechtigungen der Liste der Berechtigungen widerrufen</span><span class="sxs-lookup"><span data-stu-id="4f1a0-120">permissions the list of permissions to revoke</span></span></param>
        <summary>
            <span data-ttu-id="4f1a0-121">Eine Liste der Berechtigungen für die AD-Identität zu Zugriffstasten zu widerrufen.</span><span class="sxs-lookup"><span data-stu-id="4f1a0-121">Revoke a list of permissions for the AD identity to access keys.</span></span>
            </summary>
        <returns><span data-ttu-id="4f1a0-122">die nächste Phase der Access-richtlinienaktualisierung</span><span class="sxs-lookup"><span data-stu-id="4f1a0-122">the next stage of access policy update</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DisallowKeyPermissions">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.KeyVault.Fluent.AccessPolicy.Update.IUpdate DisallowKeyPermissions (System.Collections.Generic.IList&lt;Microsoft.Azure.Management.KeyVault.Fluent.Models.KeyPermissions&gt; permissions);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.KeyVault.Fluent.AccessPolicy.Update.IUpdate DisallowKeyPermissions(class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.KeyVault.Fluent.Models.KeyPermissions&gt; permissions) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.KeyVault.Fluent.AccessPolicy.Update.IWithPermissions.DisallowKeyPermissions(System.Collections.Generic.IList{Microsoft.Azure.Management.KeyVault.Fluent.Models.KeyPermissions})" />
      <MemberSignature Language="VB.NET" Value="Public Function DisallowKeyPermissions (permissions As IList(Of KeyPermissions)) As IUpdate" />
      <MemberSignature Language="F#" Value="abstract member DisallowKeyPermissions : System.Collections.Generic.IList&lt;Microsoft.Azure.Management.KeyVault.Fluent.Models.KeyPermissions&gt; -&gt; Microsoft.Azure.Management.KeyVault.Fluent.AccessPolicy.Update.IUpdate" Usage="iWithPermissions.DisallowKeyPermissions permissions" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.KeyVault.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.KeyVault.Fluent.AccessPolicy.Update.IUpdate</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="permissions" Type="System.Collections.Generic.IList&lt;Microsoft.Azure.Management.KeyVault.Fluent.Models.KeyPermissions&gt;" />
      </Parameters>
      <Docs>
        <param name="permissions"><span data-ttu-id="4f1a0-123">Berechtigungen der Liste der Berechtigungen widerrufen</span><span class="sxs-lookup"><span data-stu-id="4f1a0-123">permissions the list of permissions to revoke</span></span></param>
        <summary>
            <span data-ttu-id="4f1a0-124">Eine Liste der Berechtigungen für die AD-Identität zu Zugriffstasten zu widerrufen.</span><span class="sxs-lookup"><span data-stu-id="4f1a0-124">Revoke a list of permissions for the AD identity to access keys.</span></span>
            </summary>
        <returns><span data-ttu-id="4f1a0-125">die nächste Phase der Access-richtlinienaktualisierung</span><span class="sxs-lookup"><span data-stu-id="4f1a0-125">the next stage of access policy update</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DisallowSecretAllPermissions">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.KeyVault.Fluent.AccessPolicy.Update.IUpdate DisallowSecretAllPermissions ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.KeyVault.Fluent.AccessPolicy.Update.IUpdate DisallowSecretAllPermissions() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.KeyVault.Fluent.AccessPolicy.Update.IWithPermissions.DisallowSecretAllPermissions" />
      <MemberSignature Language="VB.NET" Value="Public Function DisallowSecretAllPermissions () As IUpdate" />
      <MemberSignature Language="F#" Value="abstract member DisallowSecretAllPermissions : unit -&gt; Microsoft.Azure.Management.KeyVault.Fluent.AccessPolicy.Update.IUpdate" Usage="iWithPermissions.DisallowSecretAllPermissions " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.KeyVault.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.KeyVault.Fluent.AccessPolicy.Update.IUpdate</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="4f1a0-126">Heben Sie alle Berechtigungen für die AD-Identität auf geheime Schlüssel zugreifen.</span><span class="sxs-lookup"><span data-stu-id="4f1a0-126">Revoke all permissions for the AD identity to access secrets.</span></span>
            </summary>
        <returns><span data-ttu-id="4f1a0-127">die nächste Phase der Access-richtlinienaktualisierung</span><span class="sxs-lookup"><span data-stu-id="4f1a0-127">the next stage of access policy update</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DisallowSecretPermissions">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.KeyVault.Fluent.AccessPolicy.Update.IUpdate DisallowSecretPermissions (params Microsoft.Azure.Management.KeyVault.Fluent.Models.SecretPermissions[] permissions);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.KeyVault.Fluent.AccessPolicy.Update.IUpdate DisallowSecretPermissions(class Microsoft.Azure.Management.KeyVault.Fluent.Models.SecretPermissions[] permissions) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.KeyVault.Fluent.AccessPolicy.Update.IWithPermissions.DisallowSecretPermissions(Microsoft.Azure.Management.KeyVault.Fluent.Models.SecretPermissions[])" />
      <MemberSignature Language="VB.NET" Value="Public Function DisallowSecretPermissions (ParamArray permissions As SecretPermissions()) As IUpdate" />
      <MemberSignature Language="F#" Value="abstract member DisallowSecretPermissions : Microsoft.Azure.Management.KeyVault.Fluent.Models.SecretPermissions[] -&gt; Microsoft.Azure.Management.KeyVault.Fluent.AccessPolicy.Update.IUpdate" Usage="iWithPermissions.DisallowSecretPermissions permissions" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.KeyVault.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.KeyVault.Fluent.AccessPolicy.Update.IUpdate</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="permissions" Type="Microsoft.Azure.Management.KeyVault.Fluent.Models.SecretPermissions[]">
          <Attributes>
            <Attribute>
              <AttributeName>System.ParamArray</AttributeName>
            </Attribute>
          </Attributes>
        </Parameter>
      </Parameters>
      <Docs>
        <param name="permissions"><span data-ttu-id="4f1a0-128">Berechtigungen der Liste der Berechtigungen widerrufen</span><span class="sxs-lookup"><span data-stu-id="4f1a0-128">permissions the list of permissions to revoke</span></span></param>
        <summary>
            <span data-ttu-id="4f1a0-129">Eine Liste der Berechtigungen für die AD-Identität auf geheime Schlüssel zu widerrufen.</span><span class="sxs-lookup"><span data-stu-id="4f1a0-129">Revoke a list of permissions for the AD identity to access secrets.</span></span>
            </summary>
        <returns><span data-ttu-id="4f1a0-130">die nächste Phase der Access-richtlinienaktualisierung</span><span class="sxs-lookup"><span data-stu-id="4f1a0-130">the next stage of access policy update</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DisallowSecretPermissions">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.KeyVault.Fluent.AccessPolicy.Update.IUpdate DisallowSecretPermissions (System.Collections.Generic.IList&lt;Microsoft.Azure.Management.KeyVault.Fluent.Models.SecretPermissions&gt; permissions);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.KeyVault.Fluent.AccessPolicy.Update.IUpdate DisallowSecretPermissions(class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.KeyVault.Fluent.Models.SecretPermissions&gt; permissions) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.KeyVault.Fluent.AccessPolicy.Update.IWithPermissions.DisallowSecretPermissions(System.Collections.Generic.IList{Microsoft.Azure.Management.KeyVault.Fluent.Models.SecretPermissions})" />
      <MemberSignature Language="VB.NET" Value="Public Function DisallowSecretPermissions (permissions As IList(Of SecretPermissions)) As IUpdate" />
      <MemberSignature Language="F#" Value="abstract member DisallowSecretPermissions : System.Collections.Generic.IList&lt;Microsoft.Azure.Management.KeyVault.Fluent.Models.SecretPermissions&gt; -&gt; Microsoft.Azure.Management.KeyVault.Fluent.AccessPolicy.Update.IUpdate" Usage="iWithPermissions.DisallowSecretPermissions permissions" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.KeyVault.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.KeyVault.Fluent.AccessPolicy.Update.IUpdate</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="permissions" Type="System.Collections.Generic.IList&lt;Microsoft.Azure.Management.KeyVault.Fluent.Models.SecretPermissions&gt;" />
      </Parameters>
      <Docs>
        <param name="permissions"><span data-ttu-id="4f1a0-131">Berechtigungen der Liste der Berechtigungen widerrufen</span><span class="sxs-lookup"><span data-stu-id="4f1a0-131">permissions the list of permissions to revoke</span></span></param>
        <summary>
            <span data-ttu-id="4f1a0-132">Eine Liste der Berechtigungen für die AD-Identität auf geheime Schlüssel zu widerrufen.</span><span class="sxs-lookup"><span data-stu-id="4f1a0-132">Revoke a list of permissions for the AD identity to access secrets.</span></span>
            </summary>
        <returns><span data-ttu-id="4f1a0-133">die nächste Phase der Access-richtlinienaktualisierung</span><span class="sxs-lookup"><span data-stu-id="4f1a0-133">the next stage of access policy update</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>