<Type Name="EndpointRangeDescription" FullName="Microsoft.Azure.Management.ServiceFabric.Models.EndpointRangeDescription">
  <TypeSignature Language="C#" Value="public class EndpointRangeDescription" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit EndpointRangeDescription extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.ServiceFabric.Models.EndpointRangeDescription" />
  <TypeSignature Language="VB.NET" Value="Public Class EndpointRangeDescription" />
  <TypeSignature Language="F#" Value="type EndpointRangeDescription = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.ServiceFabric</AssemblyName>
    <AssemblyVersion>1.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="1e2b4-101">Details des Bereichs</span><span class="sxs-lookup"><span data-stu-id="1e2b4-101">Port range details</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public EndpointRangeDescription ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ServiceFabric.Models.EndpointRangeDescription.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ServiceFabric</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="1e2b4-102">Initialisiert eine neue Instanz der EndpointRangeDescription-Klasse.</span><span class="sxs-lookup"><span data-stu-id="1e2b4-102">Initializes a new instance of the EndpointRangeDescription class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public EndpointRangeDescription (int startPort, int endPort);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(int32 startPort, int32 endPort) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ServiceFabric.Models.EndpointRangeDescription.#ctor(System.Int32,System.Int32)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (startPort As Integer, endPort As Integer)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.ServiceFabric.Models.EndpointRangeDescription : int * int -&gt; Microsoft.Azure.Management.ServiceFabric.Models.EndpointRangeDescription" Usage="new Microsoft.Azure.Management.ServiceFabric.Models.EndpointRangeDescription (startPort, endPort)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ServiceFabric</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="startPort" Type="System.Int32" />
        <Parameter Name="endPort" Type="System.Int32" />
      </Parameters>
      <Docs>
        <param name="startPort"><span data-ttu-id="1e2b4-103">Startport eines Bereichs von ports</span><span class="sxs-lookup"><span data-stu-id="1e2b4-103">Starting port of a range of ports</span></span></param>
        <param name="endPort"><span data-ttu-id="1e2b4-104">Der Endport eines Bereichs von ports</span><span class="sxs-lookup"><span data-stu-id="1e2b4-104">End port of a range of ports</span></span></param>
        <summary>
            <span data-ttu-id="1e2b4-105">Initialisiert eine neue Instanz der EndpointRangeDescription-Klasse.</span><span class="sxs-lookup"><span data-stu-id="1e2b4-105">Initializes a new instance of the EndpointRangeDescription class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="EndPort">
      <MemberSignature Language="C#" Value="public int EndPort { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int32 EndPort" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.ServiceFabric.Models.EndpointRangeDescription.EndPort" />
      <MemberSignature Language="VB.NET" Value="Public Property EndPort As Integer" />
      <MemberSignature Language="F#" Value="member this.EndPort : int with get, set" Usage="Microsoft.Azure.Management.ServiceFabric.Models.EndpointRangeDescription.EndPort" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ServiceFabric</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="endPort")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Int32</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="1e2b4-106">Ruft ab oder legt ihn fest Endport eines Bereichs von ports</span><span class="sxs-lookup"><span data-stu-id="1e2b4-106">Gets or sets end port of a range of ports</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="StartPort">
      <MemberSignature Language="C#" Value="public int StartPort { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int32 StartPort" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.ServiceFabric.Models.EndpointRangeDescription.StartPort" />
      <MemberSignature Language="VB.NET" Value="Public Property StartPort As Integer" />
      <MemberSignature Language="F#" Value="member this.StartPort : int with get, set" Usage="Microsoft.Azure.Management.ServiceFabric.Models.EndpointRangeDescription.StartPort" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ServiceFabric</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="startPort")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Int32</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="1e2b4-107">Ruft ab oder legt sie fest, Startport eines Bereichs von ports</span><span class="sxs-lookup"><span data-stu-id="1e2b4-107">Gets or sets starting port of a range of ports</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Validate">
      <MemberSignature Language="C#" Value="public virtual void Validate ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Validate() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ServiceFabric.Models.EndpointRangeDescription.Validate" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Sub Validate ()" />
      <MemberSignature Language="F#" Value="abstract member Validate : unit -&gt; unit&#xA;override this.Validate : unit -&gt; unit" Usage="endpointRangeDescription.Validate " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ServiceFabric</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="1e2b4-108">Überprüfen Sie das Objekt.</span><span class="sxs-lookup"><span data-stu-id="1e2b4-108">Validate the object.</span></span>
            </summary>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="1e2b4-109">Wird ausgelöst, wenn die Validierung fehlschlägt</span><span class="sxs-lookup"><span data-stu-id="1e2b4-109">Thrown if validation fails</span></span>
            </exception>
      </Docs>
    </Member>
  </Members>
</Type>