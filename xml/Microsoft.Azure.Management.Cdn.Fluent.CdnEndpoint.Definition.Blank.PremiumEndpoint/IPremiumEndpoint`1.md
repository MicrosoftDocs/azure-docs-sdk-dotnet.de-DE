<Type Name="IPremiumEndpoint&lt;ParentT&gt;" FullName="Microsoft.Azure.Management.Cdn.Fluent.CdnEndpoint.Definition.Blank.PremiumEndpoint.IPremiumEndpoint&lt;ParentT&gt;">
  <TypeSignature Language="C#" Value="public interface IPremiumEndpoint&lt;ParentT&gt;" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IPremiumEndpoint`1&lt;ParentT&gt;" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Cdn.Fluent.CdnEndpoint.Definition.Blank.PremiumEndpoint.IPremiumEndpoint`1" />
  <TypeSignature Language="VB.NET" Value="Public Interface IPremiumEndpoint(Of ParentT)" />
  <TypeSignature Language="F#" Value="type IPremiumEndpoint&lt;'ParentT&gt; = interface" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Cdn.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <TypeParameters>
    <TypeParameter Name="ParentT" />
  </TypeParameters>
  <Interfaces />
  <Docs>
    <typeparam name="ParentT"><span data-ttu-id="d0b5c-101">Die Phase des übergeordneten Elements CDN-Profildefinition wieder nach dem Anfügen dieser Definition.</span><span class="sxs-lookup"><span data-stu-id="d0b5c-101">The stage of the parent CDN profile definition to return to after attaching this definition.</span></span></typeparam>
    <summary>
            <span data-ttu-id="d0b5c-102">Die Phase einer CDN-Endpunkt Profildefinition an den Ursprung für den CDN-Profil mit der Premium-SKU Verizon ermöglicht.</span><span class="sxs-lookup"><span data-stu-id="d0b5c-102">The stage of a CDN profile endpoint definition allowing to specify the origin for the CDN profile with teh Premium Verizon SKU.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="WithPremiumOrigin">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Cdn.Fluent.CdnEndpoint.Definition.IWithPremiumAttach&lt;ParentT&gt; WithPremiumOrigin (string originHostName);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Cdn.Fluent.CdnEndpoint.Definition.IWithPremiumAttach`1&lt;!ParentT&gt; WithPremiumOrigin(string originHostName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Cdn.Fluent.CdnEndpoint.Definition.Blank.PremiumEndpoint.IPremiumEndpoint`1.WithPremiumOrigin(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function WithPremiumOrigin (originHostName As String) As IWithPremiumAttach(Of ParentT)" />
      <MemberSignature Language="F#" Value="abstract member WithPremiumOrigin : string -&gt; Microsoft.Azure.Management.Cdn.Fluent.CdnEndpoint.Definition.IWithPremiumAttach&lt;'ParentT&gt;" Usage="iPremiumEndpoint.WithPremiumOrigin originHostName" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Cdn.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Cdn.Fluent.CdnEndpoint.Definition.IWithPremiumAttach&lt;ParentT&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="originHostName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="originHostName"><span data-ttu-id="d0b5c-103">Hostname des Ursprungs.</span><span class="sxs-lookup"><span data-stu-id="d0b5c-103">Origin hostname.</span></span></param>
        <summary>
            <span data-ttu-id="d0b5c-104">Gibt den Ursprung des CDN-Endpunkts an.</span><span class="sxs-lookup"><span data-stu-id="d0b5c-104">Specifies the origin of the CDN endpoint.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return><span data-ttu-id="d0b5c-105">die nächste Phase der Definition.</span><span class="sxs-lookup"><span data-stu-id="d0b5c-105">The next stage of the definition.</span></span></return>
      </Docs>
    </Member>
    <Member MemberName="WithPremiumOrigin">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Cdn.Fluent.CdnEndpoint.Definition.IWithPremiumAttach&lt;ParentT&gt; WithPremiumOrigin (string originName, string originHostName);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Cdn.Fluent.CdnEndpoint.Definition.IWithPremiumAttach`1&lt;!ParentT&gt; WithPremiumOrigin(string originName, string originHostName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Cdn.Fluent.CdnEndpoint.Definition.Blank.PremiumEndpoint.IPremiumEndpoint`1.WithPremiumOrigin(System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function WithPremiumOrigin (originName As String, originHostName As String) As IWithPremiumAttach(Of ParentT)" />
      <MemberSignature Language="F#" Value="abstract member WithPremiumOrigin : string * string -&gt; Microsoft.Azure.Management.Cdn.Fluent.CdnEndpoint.Definition.IWithPremiumAttach&lt;'ParentT&gt;" Usage="iPremiumEndpoint.WithPremiumOrigin (originName, originHostName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Cdn.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Cdn.Fluent.CdnEndpoint.Definition.IWithPremiumAttach&lt;ParentT&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="originName" Type="System.String" />
        <Parameter Name="originHostName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="originName"><span data-ttu-id="d0b5c-106">Der Name des Ursprungs.</span><span class="sxs-lookup"><span data-stu-id="d0b5c-106">Name of the origin.</span></span></param>
        <param name="originHostName"><span data-ttu-id="d0b5c-107">Hostname des Ursprungs.</span><span class="sxs-lookup"><span data-stu-id="d0b5c-107">Origin hostname.</span></span></param>
        <summary>
            <span data-ttu-id="d0b5c-108">Gibt den Ursprung des CDN-Endpunkts an.</span><span class="sxs-lookup"><span data-stu-id="d0b5c-108">Specifies the origin of the CDN endpoint.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return><span data-ttu-id="d0b5c-109">die nächste Phase der Definition.</span><span class="sxs-lookup"><span data-stu-id="d0b5c-109">The next stage of the definition.</span></span></return>
      </Docs>
    </Member>
  </Members>
</Type>