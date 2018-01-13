<Type Name="IWithTemplate" FullName="Microsoft.Azure.Management.ResourceManager.Fluent.Deployment.Update.IWithTemplate">
  <TypeSignature Language="C#" Value="public interface IWithTemplate" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IWithTemplate" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.ResourceManager.Fluent.Deployment.Update.IWithTemplate" />
  <TypeSignature Language="VB.NET" Value="Public Interface IWithTemplate" />
  <TypeSignature Language="F#" Value="type IWithTemplate = interface" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.ResourceManager.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="80db5-101">Ein Bereitstellungsupdate, sodass um Vorlage zu ändern.</span><span class="sxs-lookup"><span data-stu-id="80db5-101">A deployment update allowing to change the template.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="WithTemplate">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.ResourceManager.Fluent.Deployment.Update.IUpdate WithTemplate (object template);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.ResourceManager.Fluent.Deployment.Update.IUpdate WithTemplate(object template) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ResourceManager.Fluent.Deployment.Update.IWithTemplate.WithTemplate(System.Object)" />
      <MemberSignature Language="VB.NET" Value="Public Function WithTemplate (template As Object) As IUpdate" />
      <MemberSignature Language="F#" Value="abstract member WithTemplate : obj -&gt; Microsoft.Azure.Management.ResourceManager.Fluent.Deployment.Update.IUpdate" Usage="iWithTemplate.WithTemplate template" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.ResourceManager.Fluent.Deployment.Update.IUpdate</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="template" Type="System.Object" />
      </Parameters>
      <Docs>
        <param name="template"><span data-ttu-id="80db5-102">das Objekt</span><span class="sxs-lookup"><span data-stu-id="80db5-102">the object</span></span></param>
        <summary>
            <span data-ttu-id="80db5-103">Gibt die Vorlage als ein Objekt an.</span><span class="sxs-lookup"><span data-stu-id="80db5-103">Specifies the template as an object.</span></span>
            </summary>
        <returns><span data-ttu-id="80db5-104">die nächste Phase der der Bereitstellung eines Updates</span><span class="sxs-lookup"><span data-stu-id="80db5-104">the next stage of the deployment update</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="WithTemplate">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.ResourceManager.Fluent.Deployment.Update.IUpdate WithTemplate (string templateJson);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.ResourceManager.Fluent.Deployment.Update.IUpdate WithTemplate(string templateJson) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ResourceManager.Fluent.Deployment.Update.IWithTemplate.WithTemplate(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function WithTemplate (templateJson As String) As IUpdate" />
      <MemberSignature Language="F#" Value="abstract member WithTemplate : string -&gt; Microsoft.Azure.Management.ResourceManager.Fluent.Deployment.Update.IUpdate" Usage="iWithTemplate.WithTemplate templateJson" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.ResourceManager.Fluent.Deployment.Update.IUpdate</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="templateJson" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="templateJson"><span data-ttu-id="80db5-105">TemplateJson die JSON-Zeichenfolge</span><span class="sxs-lookup"><span data-stu-id="80db5-105">templateJson the JSON string</span></span></param>
        <summary>
            <span data-ttu-id="80db5-106">Gibt die Vorlage als JSON-Zeichenfolge.</span><span class="sxs-lookup"><span data-stu-id="80db5-106">Specifies the template as a JSON string.</span></span>
            </summary>
        <returns><span data-ttu-id="80db5-107">die nächste Phase der der Bereitstellung eines Updates</span><span class="sxs-lookup"><span data-stu-id="80db5-107">the next stage of the deployment update</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="WithTemplateLink">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.ResourceManager.Fluent.Deployment.Update.IUpdate WithTemplateLink (string uri, string contentVersion);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.ResourceManager.Fluent.Deployment.Update.IUpdate WithTemplateLink(string uri, string contentVersion) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ResourceManager.Fluent.Deployment.Update.IWithTemplate.WithTemplateLink(System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function WithTemplateLink (uri As String, contentVersion As String) As IUpdate" />
      <MemberSignature Language="F#" Value="abstract member WithTemplateLink : string * string -&gt; Microsoft.Azure.Management.ResourceManager.Fluent.Deployment.Update.IUpdate" Usage="iWithTemplate.WithTemplateLink (uri, contentVersion)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.ResourceManager.Fluent.Deployment.Update.IUpdate</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="uri" Type="System.String" />
        <Parameter Name="contentVersion" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="uri"><span data-ttu-id="80db5-108">URI der Speicherort der remote-Vorlagendatei</span><span class="sxs-lookup"><span data-stu-id="80db5-108">uri the location of the remote template file</span></span></param>
        <param name="contentVersion"><span data-ttu-id="80db5-109">ContentVersion die Version der Vorlagendatei</span><span class="sxs-lookup"><span data-stu-id="80db5-109">contentVersion the version of the template file</span></span></param>
        <summary>
            <span data-ttu-id="80db5-110">Gibt die Vorlage als eine URL an.</span><span class="sxs-lookup"><span data-stu-id="80db5-110">Specifies the template as a URL.</span></span>
            </summary>
        <returns><span data-ttu-id="80db5-111">die nächste Phase der der Bereitstellung eines Updates</span><span class="sxs-lookup"><span data-stu-id="80db5-111">the next stage of the deployment update</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>