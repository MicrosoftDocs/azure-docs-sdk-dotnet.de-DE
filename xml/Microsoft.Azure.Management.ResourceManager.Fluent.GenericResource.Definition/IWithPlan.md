<Type Name="IWithPlan" FullName="Microsoft.Azure.Management.ResourceManager.Fluent.GenericResource.Definition.IWithPlan">
  <TypeSignature Language="C#" Value="public interface IWithPlan" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IWithPlan" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.ResourceManager.Fluent.GenericResource.Definition.IWithPlan" />
  <TypeSignature Language="VB.NET" Value="Public Interface IWithPlan" />
  <TypeSignature Language="F#" Value="type IWithPlan = interface" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.ResourceManager.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="98610-101">Planen Sie eine allgemeine Ressource Definition ermöglicht angegeben werden.</span><span class="sxs-lookup"><span data-stu-id="98610-101">A generic resource definition allowing plan to be specified.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="WithoutPlan">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.ResourceManager.Fluent.GenericResource.Definition.IWithApiVersion WithoutPlan ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.ResourceManager.Fluent.GenericResource.Definition.IWithApiVersion WithoutPlan() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ResourceManager.Fluent.GenericResource.Definition.IWithPlan.WithoutPlan" />
      <MemberSignature Language="VB.NET" Value="Public Function WithoutPlan () As IWithApiVersion" />
      <MemberSignature Language="F#" Value="abstract member WithoutPlan : unit -&gt; Microsoft.Azure.Management.ResourceManager.Fluent.GenericResource.Definition.IWithApiVersion" Usage="iWithPlan.WithoutPlan " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.ResourceManager.Fluent.GenericResource.Definition.IWithApiVersion</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="98610-102">Gibt den Plan der Ressource an.</span><span class="sxs-lookup"><span data-stu-id="98610-102">Specifies the plan of the resource.</span></span>
            </summary>
        <returns><span data-ttu-id="98610-103">die nächste Phase der Definition der allgemeine Ressource</span><span class="sxs-lookup"><span data-stu-id="98610-103">the next stage of the generic resource definition</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="WithPlan">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.ResourceManager.Fluent.GenericResource.Definition.IWithApiVersion WithPlan (string name, string publisher, string product, string promotionCode);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.ResourceManager.Fluent.GenericResource.Definition.IWithApiVersion WithPlan(string name, string publisher, string product, string promotionCode) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ResourceManager.Fluent.GenericResource.Definition.IWithPlan.WithPlan(System.String,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function WithPlan (name As String, publisher As String, product As String, promotionCode As String) As IWithApiVersion" />
      <MemberSignature Language="F#" Value="abstract member WithPlan : string * string * string * string -&gt; Microsoft.Azure.Management.ResourceManager.Fluent.GenericResource.Definition.IWithApiVersion" Usage="iWithPlan.WithPlan (name, publisher, product, promotionCode)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.ResourceManager.Fluent.GenericResource.Definition.IWithApiVersion</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="publisher" Type="System.String" />
        <Parameter Name="product" Type="System.String" />
        <Parameter Name="promotionCode" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="name"><span data-ttu-id="98610-104">Der Name des Plans</span><span class="sxs-lookup"><span data-stu-id="98610-104">name the name of the plan</span></span></param>
        <param name="publisher"><span data-ttu-id="98610-105">Verleger der Verleger des Plans</span><span class="sxs-lookup"><span data-stu-id="98610-105">publisher the publisher of the plan</span></span></param>
        <param name="product"><span data-ttu-id="98610-106">Produkt, den Namen des Produkts</span><span class="sxs-lookup"><span data-stu-id="98610-106">product the name of the product</span></span></param>
        <param name="promotionCode"><span data-ttu-id="98610-107">PromotionCode den Promotioncode, falls vorhanden</span><span class="sxs-lookup"><span data-stu-id="98610-107">promotionCode the promotion code, if any</span></span></param>
        <summary>
            <span data-ttu-id="98610-108">Gibt den Plan der Ressource an.</span><span class="sxs-lookup"><span data-stu-id="98610-108">Specifies the plan of the resource.</span></span> <span data-ttu-id="98610-109">Der Plan kann nur für 3rd Party Ressourcen festgelegt werden.</span><span class="sxs-lookup"><span data-stu-id="98610-109">The plan can only be set for 3rd party resources.</span></span>
            </summary>
        <returns><span data-ttu-id="98610-110">die nächste Phase der Definition der allgemeine Ressource</span><span class="sxs-lookup"><span data-stu-id="98610-110">the next stage of the generic resource definition</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>