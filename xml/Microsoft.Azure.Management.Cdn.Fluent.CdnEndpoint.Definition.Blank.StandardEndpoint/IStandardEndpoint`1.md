<Type Name="IStandardEndpoint&lt;ParentT&gt;" FullName="Microsoft.Azure.Management.Cdn.Fluent.CdnEndpoint.Definition.Blank.StandardEndpoint.IStandardEndpoint&lt;ParentT&gt;">
  <TypeSignature Language="C#" Value="public interface IStandardEndpoint&lt;ParentT&gt;" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IStandardEndpoint`1&lt;ParentT&gt;" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Cdn.Fluent.CdnEndpoint.Definition.Blank.StandardEndpoint.IStandardEndpoint`1" />
  <TypeSignature Language="VB.NET" Value="Public Interface IStandardEndpoint(Of ParentT)" />
  <TypeSignature Language="F#" Value="type IStandardEndpoint&lt;'ParentT&gt; = interface" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Cdn.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <TypeParameters>
    <TypeParameter Name="ParentT" />
  </TypeParameters>
  <Interfaces />
  <Docs>
    <typeparam name="ParentT"><span data-ttu-id="6a259-101">Die Phase des übergeordneten Elements CDN-Profildefinition wieder nach dem Anfügen dieser Definition.</span><span class="sxs-lookup"><span data-stu-id="6a259-101">The stage of the parent CDN profile definition to return to after attaching this definition.</span></span></typeparam>
    <summary>
            <span data-ttu-id="6a259-102">Die Phase einer CDN-Endpunkt Profildefinition ermöglicht den Ursprung angeben.</span><span class="sxs-lookup"><span data-stu-id="6a259-102">The stage of a CDN profile endpoint definition allowing to specify the origin.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="WithOrigin">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Cdn.Fluent.CdnEndpoint.Definition.IWithStandardAttach&lt;ParentT&gt; WithOrigin (string originHostName);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Cdn.Fluent.CdnEndpoint.Definition.IWithStandardAttach`1&lt;!ParentT&gt; WithOrigin(string originHostName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Cdn.Fluent.CdnEndpoint.Definition.Blank.StandardEndpoint.IStandardEndpoint`1.WithOrigin(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function WithOrigin (originHostName As String) As IWithStandardAttach(Of ParentT)" />
      <MemberSignature Language="F#" Value="abstract member WithOrigin : string -&gt; Microsoft.Azure.Management.Cdn.Fluent.CdnEndpoint.Definition.IWithStandardAttach&lt;'ParentT&gt;" Usage="iStandardEndpoint.WithOrigin originHostName" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Cdn.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Cdn.Fluent.CdnEndpoint.Definition.IWithStandardAttach&lt;ParentT&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="originHostName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="originHostName"><span data-ttu-id="6a259-103">Hostname des Ursprungs.</span><span class="sxs-lookup"><span data-stu-id="6a259-103">Origin hostname.</span></span></param>
        <summary>
            <span data-ttu-id="6a259-104">Gibt den Ursprung des CDN-Endpunkts an.</span><span class="sxs-lookup"><span data-stu-id="6a259-104">Specifies the origin of the CDN endpoint.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return><span data-ttu-id="6a259-105">die nächste Phase der Definition.</span><span class="sxs-lookup"><span data-stu-id="6a259-105">The next stage of the definition.</span></span></return>
      </Docs>
    </Member>
    <Member MemberName="WithOrigin">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Cdn.Fluent.CdnEndpoint.Definition.IWithStandardAttach&lt;ParentT&gt; WithOrigin (string originName, string originHostName);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Cdn.Fluent.CdnEndpoint.Definition.IWithStandardAttach`1&lt;!ParentT&gt; WithOrigin(string originName, string originHostName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Cdn.Fluent.CdnEndpoint.Definition.Blank.StandardEndpoint.IStandardEndpoint`1.WithOrigin(System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function WithOrigin (originName As String, originHostName As String) As IWithStandardAttach(Of ParentT)" />
      <MemberSignature Language="F#" Value="abstract member WithOrigin : string * string -&gt; Microsoft.Azure.Management.Cdn.Fluent.CdnEndpoint.Definition.IWithStandardAttach&lt;'ParentT&gt;" Usage="iStandardEndpoint.WithOrigin (originName, originHostName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Cdn.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Cdn.Fluent.CdnEndpoint.Definition.IWithStandardAttach&lt;ParentT&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="originName" Type="System.String" />
        <Parameter Name="originHostName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="originName"><span data-ttu-id="6a259-106">Der Name des Ursprungs.</span><span class="sxs-lookup"><span data-stu-id="6a259-106">Name of the origin.</span></span></param>
        <param name="originHostName"><span data-ttu-id="6a259-107">Hostname des Ursprungs.</span><span class="sxs-lookup"><span data-stu-id="6a259-107">Origin hostname.</span></span></param>
        <summary>
            <span data-ttu-id="6a259-108">Gibt den Ursprung des CDN-Endpunkts an.</span><span class="sxs-lookup"><span data-stu-id="6a259-108">Specifies the origin of the CDN endpoint.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return><span data-ttu-id="6a259-109">die nächste Phase der Definition.</span><span class="sxs-lookup"><span data-stu-id="6a259-109">The next stage of the definition.</span></span></return>
      </Docs>
    </Member>
  </Members>
</Type>