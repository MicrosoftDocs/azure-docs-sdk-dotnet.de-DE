<Type Name="RegenerateKeysParameters" FullName="Microsoft.Azure.Management.ServiceBus.Fluent.Models.RegenerateKeysParameters">
  <TypeSignature Language="C#" Value="public class RegenerateKeysParameters" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit RegenerateKeysParameters extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.ServiceBus.Fluent.Models.RegenerateKeysParameters" />
  <TypeSignature Language="VB.NET" Value="Public Class RegenerateKeysParameters" />
  <TypeSignature Language="F#" Value="type RegenerateKeysParameters = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.ServiceBus.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="81ec2-101">Parameter für die Autorisierungsregel Regenerieren zur Verfügung gestellt.</span><span class="sxs-lookup"><span data-stu-id="81ec2-101">Parameters supplied to the Regenerate Authorization Rule operation.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public RegenerateKeysParameters ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ServiceBus.Fluent.Models.RegenerateKeysParameters.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ServiceBus.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="81ec2-102">Initialisiert eine neue Instanz der RegenerateKeysParameters-Klasse.</span><span class="sxs-lookup"><span data-stu-id="81ec2-102">Initializes a new instance of the RegenerateKeysParameters class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public RegenerateKeysParameters (Nullable&lt;Microsoft.Azure.Management.ServiceBus.Fluent.Models.Policykey&gt; policykey = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.ServiceBus.Fluent.Models.Policykey&gt; policykey) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ServiceBus.Fluent.Models.RegenerateKeysParameters.#ctor(System.Nullable{Microsoft.Azure.Management.ServiceBus.Fluent.Models.Policykey})" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional policykey As Nullable(Of Policykey) = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.ServiceBus.Fluent.Models.RegenerateKeysParameters : Nullable&lt;Microsoft.Azure.Management.ServiceBus.Fluent.Models.Policykey&gt; -&gt; Microsoft.Azure.Management.ServiceBus.Fluent.Models.RegenerateKeysParameters" Usage="new Microsoft.Azure.Management.ServiceBus.Fluent.Models.RegenerateKeysParameters policykey" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ServiceBus.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="policykey" Type="System.Nullable&lt;Microsoft.Azure.Management.ServiceBus.Fluent.Models.Policykey&gt;" />
      </Parameters>
      <Docs>
        <param name="policykey"><span data-ttu-id="81ec2-103">Schlüssel, der neu generiert werden muss.</span><span class="sxs-lookup"><span data-stu-id="81ec2-103">Key that needs to be regenerated.</span></span> <span data-ttu-id="81ec2-104">Folgende Werte sind möglich: "PrimaryKey", "SecondaryKey"</span><span class="sxs-lookup"><span data-stu-id="81ec2-104">Possible values include: 'PrimaryKey', 'SecondaryKey'</span></span></param>
        <summary>
            <span data-ttu-id="81ec2-105">Initialisiert eine neue Instanz der RegenerateKeysParameters-Klasse.</span><span class="sxs-lookup"><span data-stu-id="81ec2-105">Initializes a new instance of the RegenerateKeysParameters class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Policykey">
      <MemberSignature Language="C#" Value="public Nullable&lt;Microsoft.Azure.Management.ServiceBus.Fluent.Models.Policykey&gt; Policykey { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.ServiceBus.Fluent.Models.Policykey&gt; Policykey" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.ServiceBus.Fluent.Models.RegenerateKeysParameters.Policykey" />
      <MemberSignature Language="VB.NET" Value="Public Property Policykey As Nullable(Of Policykey)" />
      <MemberSignature Language="F#" Value="member this.Policykey : Nullable&lt;Microsoft.Azure.Management.ServiceBus.Fluent.Models.Policykey&gt; with get, set" Usage="Microsoft.Azure.Management.ServiceBus.Fluent.Models.RegenerateKeysParameters.Policykey" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ServiceBus.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="policykey")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;Microsoft.Azure.Management.ServiceBus.Fluent.Models.Policykey&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="81ec2-106">Abrufen oder Festlegen der Schlüssel, der neu generiert werden muss.</span><span class="sxs-lookup"><span data-stu-id="81ec2-106">Gets or sets key that needs to be regenerated.</span></span> <span data-ttu-id="81ec2-107">Folgende Werte sind möglich: "PrimaryKey", "SecondaryKey"</span><span class="sxs-lookup"><span data-stu-id="81ec2-107">Possible values include: 'PrimaryKey', 'SecondaryKey'</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>