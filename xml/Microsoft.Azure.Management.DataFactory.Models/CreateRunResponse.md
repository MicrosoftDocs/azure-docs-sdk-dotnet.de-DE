<Type Name="CreateRunResponse" FullName="Microsoft.Azure.Management.DataFactory.Models.CreateRunResponse">
  <TypeSignature Language="C#" Value="public class CreateRunResponse" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit CreateRunResponse extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.DataFactory.Models.CreateRunResponse" />
  <TypeSignature Language="VB.NET" Value="Public Class CreateRunResponse" />
  <TypeSignature Language="F#" Value="type CreateRunResponse = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
    <AssemblyVersion>0.2.0.0</AssemblyVersion>
    <AssemblyVersion>0.3.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="4c821-101">Der Antworttext mit einem Bezeichner ausführen.</span><span class="sxs-lookup"><span data-stu-id="4c821-101">Response body with a run identifier.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public CreateRunResponse ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactory.Models.CreateRunResponse.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.2.0.0</AssemblyVersion>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="4c821-102">Initialisiert eine neue Instanz der CreateRunResponse-Klasse.</span><span class="sxs-lookup"><span data-stu-id="4c821-102">Initializes a new instance of the CreateRunResponse class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public CreateRunResponse (string runId);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string runId) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactory.Models.CreateRunResponse.#ctor(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (runId As String)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.DataFactory.Models.CreateRunResponse : string -&gt; Microsoft.Azure.Management.DataFactory.Models.CreateRunResponse" Usage="new Microsoft.Azure.Management.DataFactory.Models.CreateRunResponse runId" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.2.0.0</AssemblyVersion>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="runId" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="runId"><span data-ttu-id="4c821-103">Der Bezeichner eines Testlaufs.</span><span class="sxs-lookup"><span data-stu-id="4c821-103">Identifier of a run.</span></span></param>
        <summary>
            <span data-ttu-id="4c821-104">Initialisiert eine neue Instanz der CreateRunResponse-Klasse.</span><span class="sxs-lookup"><span data-stu-id="4c821-104">Initializes a new instance of the CreateRunResponse class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RunId">
      <MemberSignature Language="C#" Value="public string RunId { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string RunId" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactory.Models.CreateRunResponse.RunId" />
      <MemberSignature Language="VB.NET" Value="Public Property RunId As String" />
      <MemberSignature Language="F#" Value="member this.RunId : string with get, set" Usage="Microsoft.Azure.Management.DataFactory.Models.CreateRunResponse.RunId" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.2.0.0</AssemblyVersion>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="runId")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="4c821-105">Ruft ab oder legt diesen fest eines Testlaufs.</span><span class="sxs-lookup"><span data-stu-id="4c821-105">Gets or sets identifier of a run.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Validate">
      <MemberSignature Language="C#" Value="public virtual void Validate ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Validate() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactory.Models.CreateRunResponse.Validate" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Sub Validate ()" />
      <MemberSignature Language="F#" Value="abstract member Validate : unit -&gt; unit&#xA;override this.Validate : unit -&gt; unit" Usage="createRunResponse.Validate " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.2.0.0</AssemblyVersion>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="4c821-106">Überprüfen Sie das Objekt.</span><span class="sxs-lookup"><span data-stu-id="4c821-106">Validate the object.</span></span>
            </summary>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="4c821-107">Wird ausgelöst, wenn die Validierung fehlschlägt</span><span class="sxs-lookup"><span data-stu-id="4c821-107">Thrown if validation fails</span></span>
            </exception>
      </Docs>
    </Member>
  </Members>
</Type>