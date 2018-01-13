<Type Name="ParameterSpecification" FullName="Microsoft.Azure.Management.DataFactory.Models.ParameterSpecification">
  <TypeSignature Language="C#" Value="public class ParameterSpecification" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit ParameterSpecification extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.DataFactory.Models.ParameterSpecification" />
  <TypeSignature Language="VB.NET" Value="Public Class ParameterSpecification" />
  <TypeSignature Language="F#" Value="type ParameterSpecification = class" />
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
            <span data-ttu-id="19096-101">Die Definition eines einzelnen Parameters für eine Entität.</span><span class="sxs-lookup"><span data-stu-id="19096-101">Definition of a single parameter for an entity.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ParameterSpecification ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactory.Models.ParameterSpecification.#ctor" />
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
            <span data-ttu-id="19096-102">Initialisiert eine neue Instanz der ParameterSpecification-Klasse.</span><span class="sxs-lookup"><span data-stu-id="19096-102">Initializes a new instance of the ParameterSpecification class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ParameterSpecification (string type, object defaultValue = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string type, object defaultValue) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactory.Models.ParameterSpecification.#ctor(System.String,System.Object)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (type As String, Optional defaultValue As Object = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.DataFactory.Models.ParameterSpecification : string * obj -&gt; Microsoft.Azure.Management.DataFactory.Models.ParameterSpecification" Usage="new Microsoft.Azure.Management.DataFactory.Models.ParameterSpecification (type, defaultValue)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.2.0.0</AssemblyVersion>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="type" Type="System.String" />
        <Parameter Name="defaultValue" Type="System.Object" />
      </Parameters>
      <Docs>
        <param name="type"><span data-ttu-id="19096-103">Der Parametertyp.</span><span class="sxs-lookup"><span data-stu-id="19096-103">Parameter type.</span></span> <span data-ttu-id="19096-104">Folgende Werte sind möglich: "Object", "String", "Int", "Float", "Bool", "Array"</span><span class="sxs-lookup"><span data-stu-id="19096-104">Possible values include: 'Object', 'String', 'Int', 'Float', 'Bool', 'Array'</span></span></param>
        <param name="defaultValue"><span data-ttu-id="19096-105">Der Standardwert des Parameters.</span><span class="sxs-lookup"><span data-stu-id="19096-105">Default value of parameter.</span></span></param>
        <summary>
            <span data-ttu-id="19096-106">Initialisiert eine neue Instanz der ParameterSpecification-Klasse.</span><span class="sxs-lookup"><span data-stu-id="19096-106">Initializes a new instance of the ParameterSpecification class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DefaultValue">
      <MemberSignature Language="C#" Value="public object DefaultValue { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance object DefaultValue" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactory.Models.ParameterSpecification.DefaultValue" />
      <MemberSignature Language="VB.NET" Value="Public Property DefaultValue As Object" />
      <MemberSignature Language="F#" Value="member this.DefaultValue : obj with get, set" Usage="Microsoft.Azure.Management.DataFactory.Models.ParameterSpecification.DefaultValue" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.2.0.0</AssemblyVersion>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="defaultValue")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Object</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="19096-107">Ruft ab oder legt Standardwert des Parameters.</span><span class="sxs-lookup"><span data-stu-id="19096-107">Gets or sets default value of parameter.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Type">
      <MemberSignature Language="C#" Value="public string Type { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Type" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactory.Models.ParameterSpecification.Type" />
      <MemberSignature Language="VB.NET" Value="Public Property Type As String" />
      <MemberSignature Language="F#" Value="member this.Type : string with get, set" Usage="Microsoft.Azure.Management.DataFactory.Models.ParameterSpecification.Type" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.2.0.0</AssemblyVersion>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="type")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="19096-108">Ruft ab oder legt ihn fest Parameter.</span><span class="sxs-lookup"><span data-stu-id="19096-108">Gets or sets parameter type.</span></span> <span data-ttu-id="19096-109">Folgende Werte sind möglich: "Object", "String", "Int", "Float", "Bool", "Array"</span><span class="sxs-lookup"><span data-stu-id="19096-109">Possible values include: 'Object', 'String', 'Int', 'Float', 'Bool', 'Array'</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Validate">
      <MemberSignature Language="C#" Value="public virtual void Validate ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Validate() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactory.Models.ParameterSpecification.Validate" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Sub Validate ()" />
      <MemberSignature Language="F#" Value="abstract member Validate : unit -&gt; unit&#xA;override this.Validate : unit -&gt; unit" Usage="parameterSpecification.Validate " />
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
            <span data-ttu-id="19096-110">Überprüfen Sie das Objekt.</span><span class="sxs-lookup"><span data-stu-id="19096-110">Validate the object.</span></span>
            </summary>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="19096-111">Wird ausgelöst, wenn die Validierung fehlschlägt</span><span class="sxs-lookup"><span data-stu-id="19096-111">Thrown if validation fails</span></span>
            </exception>
      </Docs>
    </Member>
  </Members>
</Type>