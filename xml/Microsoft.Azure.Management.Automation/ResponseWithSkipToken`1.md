<Type Name="ResponseWithSkipToken&lt;T&gt;" FullName="Microsoft.Azure.Management.Automation.ResponseWithSkipToken&lt;T&gt;">
  <TypeSignature Language="C#" Value="public class ResponseWithSkipToken&lt;T&gt;" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit ResponseWithSkipToken`1&lt;T&gt; extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Automation.ResponseWithSkipToken`1" />
  <TypeSignature Language="VB.NET" Value="Public Class ResponseWithSkipToken(Of T)" />
  <TypeSignature Language="F#" Value="type ResponseWithSkipToken&lt;'T&gt; = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Automation</AssemblyName>
    <AssemblyVersion>2.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <TypeParameters>
    <TypeParameter Name="T" />
  </TypeParameters>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <typeparam name="T"></typeparam>
    <summary>
            <span data-ttu-id="08596-101">Die Antwort mit Skip-Token.</span><span class="sxs-lookup"><span data-stu-id="08596-101">The response with skip token.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ResponseWithSkipToken (Microsoft.Azure.Management.Automation.Models.OperationResponseWithSkipToken operationResponseWithSkipToken, System.Collections.Generic.IEnumerable&lt;T&gt; automationManagementModels);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class Microsoft.Azure.Management.Automation.Models.OperationResponseWithSkipToken operationResponseWithSkipToken, class System.Collections.Generic.IEnumerable`1&lt;!T&gt; automationManagementModels) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Automation.ResponseWithSkipToken`1.#ctor(Microsoft.Azure.Management.Automation.Models.OperationResponseWithSkipToken,System.Collections.Generic.IEnumerable{`0})" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.Automation.ResponseWithSkipToken&lt;'T&gt; : Microsoft.Azure.Management.Automation.Models.OperationResponseWithSkipToken * seq&lt;'T&gt; -&gt; Microsoft.Azure.Management.Automation.ResponseWithSkipToken&lt;'T&gt;" Usage="new Microsoft.Azure.Management.Automation.ResponseWithSkipToken&lt;'T&gt; (operationResponseWithSkipToken, automationManagementModels)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Automation</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="operationResponseWithSkipToken" Type="Microsoft.Azure.Management.Automation.Models.OperationResponseWithSkipToken" />
        <Parameter Name="automationManagementModels" Type="System.Collections.Generic.IEnumerable&lt;T&gt;" />
      </Parameters>
      <Docs>
        <param name="operationResponseWithSkipToken">
            <span data-ttu-id="08596-102">Antworten für den Vorgang mit Skip-Token.</span><span class="sxs-lookup"><span data-stu-id="08596-102">The operation response with skip token.</span></span>
            </param>
        <param name="automationManagementModels">
            <span data-ttu-id="08596-103">Die Automatisierung Management-Modelle.</span><span class="sxs-lookup"><span data-stu-id="08596-103">The automation management models.</span></span>
            </param>
        <summary>
            <span data-ttu-id="08596-104">Initialisiert eine neue Instanz der <see cref="T:Microsoft.Azure.Management.Automation.ResponseWithSkipToken`1" />-Klasse.</span><span class="sxs-lookup"><span data-stu-id="08596-104">Initializes a new instance of the <see cref="T:Microsoft.Azure.Management.Automation.ResponseWithSkipToken`1" /> class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
        <exception cref="T:System.ArgumentNullException">
            <span data-ttu-id="08596-105">Argument Null-Ausnahme</span><span class="sxs-lookup"><span data-stu-id="08596-105">Argument Null Exception</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="AutomationManagementModels">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IEnumerable&lt;T&gt; AutomationManagementModels { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IEnumerable`1&lt;!T&gt; AutomationManagementModels" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Automation.ResponseWithSkipToken`1.AutomationManagementModels" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property AutomationManagementModels As IEnumerable(Of T)" />
      <MemberSignature Language="F#" Value="member this.AutomationManagementModels : seq&lt;'T&gt;" Usage="Microsoft.Azure.Management.Automation.ResponseWithSkipToken&lt;'T&gt;.AutomationManagementModels" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Automation</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IEnumerable&lt;T&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="08596-106">Ruft die Automatisierung Management Modelle ab.</span><span class="sxs-lookup"><span data-stu-id="08596-106">Gets the automation management models.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SkipToken">
      <MemberSignature Language="C#" Value="public string SkipToken { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string SkipToken" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Automation.ResponseWithSkipToken`1.SkipToken" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property SkipToken As String" />
      <MemberSignature Language="F#" Value="member this.SkipToken : string" Usage="Microsoft.Azure.Management.Automation.ResponseWithSkipToken&lt;'T&gt;.SkipToken" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Automation</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="08596-107">Ruft die Skip-token ab.</span><span class="sxs-lookup"><span data-stu-id="08596-107">Gets the skip token.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>