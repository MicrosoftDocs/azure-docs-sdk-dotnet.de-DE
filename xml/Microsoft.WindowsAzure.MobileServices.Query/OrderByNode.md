<Type Name="OrderByNode" FullName="Microsoft.WindowsAzure.MobileServices.Query.OrderByNode">
  <TypeSignature Language="C#" Value="public class OrderByNode" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit OrderByNode extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.WindowsAzure.MobileServices.Query.OrderByNode" />
  <TypeSignature Language="VB.NET" Value="Public Class OrderByNode" />
  <TypeSignature Language="F#" Value="type OrderByNode = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Mobile.Client</AssemblyName>
    <AssemblyVersion>4.0.0.0</AssemblyVersion>
    <AssemblyVersion>4.0.2.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="d807f-101">Stellt das Analyseergebnis einer $orderby-Abfrageoption dar.</span><span class="sxs-lookup"><span data-stu-id="d807f-101">Represents the result of parsing the $orderby query option.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public OrderByNode (Microsoft.WindowsAzure.MobileServices.Query.QueryNode expression, Microsoft.WindowsAzure.MobileServices.Query.OrderByDirection direction);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class Microsoft.WindowsAzure.MobileServices.Query.QueryNode expression, valuetype Microsoft.WindowsAzure.MobileServices.Query.OrderByDirection direction) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.MobileServices.Query.OrderByNode.#ctor(Microsoft.WindowsAzure.MobileServices.Query.QueryNode,Microsoft.WindowsAzure.MobileServices.Query.OrderByDirection)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (expression As QueryNode, direction As OrderByDirection)" />
      <MemberSignature Language="F#" Value="new Microsoft.WindowsAzure.MobileServices.Query.OrderByNode : Microsoft.WindowsAzure.MobileServices.Query.QueryNode * Microsoft.WindowsAzure.MobileServices.Query.OrderByDirection -&gt; Microsoft.WindowsAzure.MobileServices.Query.OrderByNode" Usage="new Microsoft.WindowsAzure.MobileServices.Query.OrderByNode (expression, direction)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Mobile.Client</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.2.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="expression" Type="Microsoft.WindowsAzure.MobileServices.Query.QueryNode" />
        <Parameter Name="direction" Type="Microsoft.WindowsAzure.MobileServices.Query.OrderByDirection" />
      </Parameters>
      <Docs>
        <param name="expression"><span data-ttu-id="d807f-102">Der Order-By-Ausdruck.</span><span class="sxs-lookup"><span data-stu-id="d807f-102">The order-by expression.</span></span></param>
        <param name="direction"><span data-ttu-id="d807f-103">Die Sortierrichtung.</span><span class="sxs-lookup"><span data-stu-id="d807f-103">The direction to order.</span></span></param>
        <summary>
            <span data-ttu-id="d807f-104">Initialisiert eine Instanz von<see cref="T:Microsoft.WindowsAzure.MobileServices.Query.OrderByNode" /></span><span class="sxs-lookup"><span data-stu-id="d807f-104">Initializes an instance of <see cref="T:Microsoft.WindowsAzure.MobileServices.Query.OrderByNode" /></span></span></summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Direction">
      <MemberSignature Language="C#" Value="public Microsoft.WindowsAzure.MobileServices.Query.OrderByDirection Direction { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype Microsoft.WindowsAzure.MobileServices.Query.OrderByDirection Direction" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.MobileServices.Query.OrderByNode.Direction" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Direction As OrderByDirection" />
      <MemberSignature Language="F#" Value="member this.Direction : Microsoft.WindowsAzure.MobileServices.Query.OrderByDirection" Usage="Microsoft.WindowsAzure.MobileServices.Query.OrderByNode.Direction" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Mobile.Client</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.2.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.WindowsAzure.MobileServices.Query.OrderByDirection</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="d807f-105">Ruft die Sortierrichtung ab.</span><span class="sxs-lookup"><span data-stu-id="d807f-105">Gets the direction to order.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Expression">
      <MemberSignature Language="C#" Value="public Microsoft.WindowsAzure.MobileServices.Query.QueryNode Expression { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.WindowsAzure.MobileServices.Query.QueryNode Expression" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.MobileServices.Query.OrderByNode.Expression" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Expression As QueryNode" />
      <MemberSignature Language="F#" Value="member this.Expression : Microsoft.WindowsAzure.MobileServices.Query.QueryNode" Usage="Microsoft.WindowsAzure.MobileServices.Query.OrderByNode.Expression" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Mobile.Client</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.2.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.WindowsAzure.MobileServices.Query.QueryNode</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="d807f-106">Ruft den Order-By-Ausdruck ab.</span><span class="sxs-lookup"><span data-stu-id="d807f-106">Gets the order-by expression.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>