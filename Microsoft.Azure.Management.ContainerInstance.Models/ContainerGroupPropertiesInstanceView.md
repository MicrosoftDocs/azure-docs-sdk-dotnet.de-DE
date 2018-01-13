<Type Name="ContainerGroupPropertiesInstanceView" FullName="Microsoft.Azure.Management.ContainerInstance.Models.ContainerGroupPropertiesInstanceView">
  <TypeSignature Language="C#" Value="public class ContainerGroupPropertiesInstanceView" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit ContainerGroupPropertiesInstanceView extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.ContainerInstance.Models.ContainerGroupPropertiesInstanceView" />
  <TypeSignature Language="VB.NET" Value="Public Class ContainerGroupPropertiesInstanceView" />
  <TypeSignature Language="F#" Value="type ContainerGroupPropertiesInstanceView = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.ContainerInstance</AssemblyName>
    <AssemblyVersion>0.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="e763c-101">Die Instanzansicht der Gruppe "Container".</span><span class="sxs-lookup"><span data-stu-id="e763c-101">The instance view of the container group.</span></span> <span data-ttu-id="e763c-102">In der Antwort nur gültig.</span><span class="sxs-lookup"><span data-stu-id="e763c-102">Only valid in response.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ContainerGroupPropertiesInstanceView ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ContainerInstance.Models.ContainerGroupPropertiesInstanceView.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ContainerInstance</AssemblyName>
        <AssemblyVersion>0.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="e763c-103">Initialisiert eine neue Instanz der ContainerGroupPropertiesInstanceView-Klasse.</span><span class="sxs-lookup"><span data-stu-id="e763c-103">Initializes a new instance of the ContainerGroupPropertiesInstanceView class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ContainerGroupPropertiesInstanceView (System.Collections.Generic.IList&lt;Microsoft.Azure.Management.ContainerInstance.Models.EventModel&gt; events = null, string state = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.ContainerInstance.Models.EventModel&gt; events, string state) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ContainerInstance.Models.ContainerGroupPropertiesInstanceView.#ctor(System.Collections.Generic.IList{Microsoft.Azure.Management.ContainerInstance.Models.EventModel},System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional events As IList(Of EventModel) = null, Optional state As String = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.ContainerInstance.Models.ContainerGroupPropertiesInstanceView : System.Collections.Generic.IList&lt;Microsoft.Azure.Management.ContainerInstance.Models.EventModel&gt; * string -&gt; Microsoft.Azure.Management.ContainerInstance.Models.ContainerGroupPropertiesInstanceView" Usage="new Microsoft.Azure.Management.ContainerInstance.Models.ContainerGroupPropertiesInstanceView (events, state)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ContainerInstance</AssemblyName>
        <AssemblyVersion>0.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="events" Type="System.Collections.Generic.IList&lt;Microsoft.Azure.Management.ContainerInstance.Models.EventModel&gt;" />
        <Parameter Name="state" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="events"><span data-ttu-id="e763c-104">Die Ereignisse dieser Container-Gruppe.</span><span class="sxs-lookup"><span data-stu-id="e763c-104">The events of this container group.</span></span></param>
        <param name="state"><span data-ttu-id="e763c-105">Der Status der Gruppe "Container".</span><span class="sxs-lookup"><span data-stu-id="e763c-105">The state of the container group.</span></span> <span data-ttu-id="e763c-106">In der Antwort nur gültig.</span><span class="sxs-lookup"><span data-stu-id="e763c-106">Only valid in response.</span></span></param>
        <summary>
            <span data-ttu-id="e763c-107">Initialisiert eine neue Instanz der ContainerGroupPropertiesInstanceView-Klasse.</span><span class="sxs-lookup"><span data-stu-id="e763c-107">Initializes a new instance of the ContainerGroupPropertiesInstanceView class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Events">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;Microsoft.Azure.Management.ContainerInstance.Models.EventModel&gt; Events { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.ContainerInstance.Models.EventModel&gt; Events" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.ContainerInstance.Models.ContainerGroupPropertiesInstanceView.Events" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Events As IList(Of EventModel)" />
      <MemberSignature Language="F#" Value="member this.Events : System.Collections.Generic.IList&lt;Microsoft.Azure.Management.ContainerInstance.Models.EventModel&gt;" Usage="Microsoft.Azure.Management.ContainerInstance.Models.ContainerGroupPropertiesInstanceView.Events" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ContainerInstance</AssemblyName>
        <AssemblyVersion>0.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="events")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;Microsoft.Azure.Management.ContainerInstance.Models.EventModel&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="e763c-108">Ruft die Ereignisse dieser Gruppe Container ab.</span><span class="sxs-lookup"><span data-stu-id="e763c-108">Gets the events of this container group.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="State">
      <MemberSignature Language="C#" Value="public string State { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string State" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.ContainerInstance.Models.ContainerGroupPropertiesInstanceView.State" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property State As String" />
      <MemberSignature Language="F#" Value="member this.State : string" Usage="Microsoft.Azure.Management.ContainerInstance.Models.ContainerGroupPropertiesInstanceView.State" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ContainerInstance</AssemblyName>
        <AssemblyVersion>0.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="state")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="e763c-109">Ruft den Status der Gruppe "Container" ab.</span><span class="sxs-lookup"><span data-stu-id="e763c-109">Gets the state of the container group.</span></span> <span data-ttu-id="e763c-110">In der Antwort nur gültig.</span><span class="sxs-lookup"><span data-stu-id="e763c-110">Only valid in response.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>