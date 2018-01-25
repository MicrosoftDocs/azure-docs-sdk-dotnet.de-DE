<Type Name="AccessCondition" FullName="Microsoft.Azure.Documents.Client.AccessCondition">
  <TypeSignature Language="C#" Value="public sealed class AccessCondition" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed beforefieldinit AccessCondition extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Documents.Client.AccessCondition" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class AccessCondition" />
  <TypeSignature Language="F#" Value="type AccessCondition = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.DocumentDB.Core</AssemblyName>
    <AssemblyVersion>1.6.0.0</AssemblyVersion>
    <AssemblyVersion>1.7.0.0</AssemblyVersion>
    <AssemblyVersion>1.7.1.0</AssemblyVersion>
  </AssemblyInfo>
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Documents.Client</AssemblyName>
    <AssemblyVersion>1.18.0.0</AssemblyVersion>
    <AssemblyVersion>1.19.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="f2cc7-101">Stellt einen Satz von zugriffsbedingungen für Vorgänge in der Azure-Cosmos-DB-Dienst verwendet werden soll.</span><span class="sxs-lookup"><span data-stu-id="f2cc7-101">Represents a set of access conditions to be used for operations in the Azure Cosmos DB service.</span></span>
            </summary>
    <remarks>To be added.</remarks>
    <altmember cref="T:Microsoft.Azure.Documents.Client.AccessConditionType" />
    <altmember cref="T:Microsoft.Azure.Documents.Client.RequestOptions" />
    <altmember cref="T:Microsoft.Azure.Documents.Resource" />
    <example>
            <span data-ttu-id="f2cc7-102">Im folgende Beispiel wird gezeigt, wie AccessCondition mit DocumentClient verwendet wird.</span><span class="sxs-lookup"><span data-stu-id="f2cc7-102">The following example shows how to use AccessCondition with DocumentClient.</span></span>
            <code language="c#"><![CDATA[
            // If ETag is current, then this will succeed. Otherwise the request will fail with HTTP 412 Precondition Failure
            await client.ReplaceDocumentAsync(
                readCopyOfBook.SelfLink, 
                new Book { Title = "Moby Dick", Price = 14.99 },
                new RequestOptions 
                { 
                    AccessCondition = new AccessCondition 
                    { 
                        Condition = readCopyOfBook.ETag, 
                        Type = AccessConditionType.IfMatch 
                    } 
                 });
            ]]></code></example>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public AccessCondition ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Documents.Client.AccessCondition.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.DocumentDB.Core</AssemblyName>
        <AssemblyVersion>1.6.0.0</AssemblyVersion>
        <AssemblyVersion>1.7.0.0</AssemblyVersion>
        <AssemblyVersion>1.7.1.0</AssemblyVersion>
      </AssemblyInfo>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Documents.Client</AssemblyName>
        <AssemblyVersion>1.18.0.0</AssemblyVersion>
        <AssemblyVersion>1.19.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>To be added.</summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Condition">
      <MemberSignature Language="C#" Value="public string Condition { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Condition" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Documents.Client.AccessCondition.Condition" />
      <MemberSignature Language="VB.NET" Value="Public Property Condition As String" />
      <MemberSignature Language="F#" Value="member this.Condition : string with get, set" Usage="Microsoft.Azure.Documents.Client.AccessCondition.Condition" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.DocumentDB.Core</AssemblyName>
        <AssemblyVersion>1.6.0.0</AssemblyVersion>
        <AssemblyVersion>1.7.0.0</AssemblyVersion>
        <AssemblyVersion>1.7.1.0</AssemblyVersion>
      </AssemblyInfo>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Documents.Client</AssemblyName>
        <AssemblyVersion>1.18.0.0</AssemblyVersion>
        <AssemblyVersion>1.19.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="f2cc7-103">Ruft ab oder legt den Wert der Bedingung in der Azure-Cosmos-DB-Dienst.</span><span class="sxs-lookup"><span data-stu-id="f2cc7-103">Gets or sets the value of the condition in the Azure Cosmos DB service.</span></span>
            </summary>
        <value>
            <span data-ttu-id="f2cc7-104">Der Wert der Bedingung.</span><span class="sxs-lookup"><span data-stu-id="f2cc7-104">The value of the condition.</span></span> <span data-ttu-id="f2cc7-105">Für <see cref="T:Microsoft.Azure.Documents.Client.AccessConditionType" /> "IfMatch" und IfNotMatch, dies ist das ETag, die verglichen werden.</span><span class="sxs-lookup"><span data-stu-id="f2cc7-105">For <see cref="T:Microsoft.Azure.Documents.Client.AccessConditionType" /> IfMatch and IfNotMatch, this is the ETag that has to be compared to.</span></span>
            </value>
        <remarks>To be added.</remarks>
        <altmember cref="T:Microsoft.Azure.Documents.Resource" />
      </Docs>
    </Member>
    <Member MemberName="Type">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Documents.Client.AccessConditionType Type { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype Microsoft.Azure.Documents.Client.AccessConditionType Type" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Documents.Client.AccessCondition.Type" />
      <MemberSignature Language="VB.NET" Value="Public Property Type As AccessConditionType" />
      <MemberSignature Language="F#" Value="member this.Type : Microsoft.Azure.Documents.Client.AccessConditionType with get, set" Usage="Microsoft.Azure.Documents.Client.AccessCondition.Type" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.DocumentDB.Core</AssemblyName>
        <AssemblyVersion>1.6.0.0</AssemblyVersion>
        <AssemblyVersion>1.7.0.0</AssemblyVersion>
        <AssemblyVersion>1.7.1.0</AssemblyVersion>
      </AssemblyInfo>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Documents.Client</AssemblyName>
        <AssemblyVersion>1.18.0.0</AssemblyVersion>
        <AssemblyVersion>1.19.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Documents.Client.AccessConditionType</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="f2cc7-106">Ruft ab oder legt den Bedingungstyp im Azure-Cosmos-DB-Dienst.</span><span class="sxs-lookup"><span data-stu-id="f2cc7-106">Gets or sets the condition type in the Azure Cosmos DB service.</span></span>
            </summary>
        <value>
            <span data-ttu-id="f2cc7-107">Der Bedingungstyp.</span><span class="sxs-lookup"><span data-stu-id="f2cc7-107">The condition type.</span></span> <span data-ttu-id="f2cc7-108">Dem IfMatch oder "ifnonematch" möglich.</span><span class="sxs-lookup"><span data-stu-id="f2cc7-108">Can be IfMatch or IfNoneMatch.</span></span>
            </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>