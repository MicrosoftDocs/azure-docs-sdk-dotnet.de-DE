<Type Name="ScaleCapacity" FullName="Microsoft.Azure.Management.Monitor.Management.Models.ScaleCapacity">
  <TypeSignature Language="C#" Value="public class ScaleCapacity" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit ScaleCapacity extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Monitor.Management.Models.ScaleCapacity" />
  <TypeSignature Language="VB.NET" Value="Public Class ScaleCapacity" />
  <TypeSignature Language="F#" Value="type ScaleCapacity = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Monitor</AssemblyName>
    <AssemblyVersion>0.18.0.0</AssemblyVersion>
    <AssemblyVersion>0.18.1.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="0aa31-101">Die Anzahl der Instanzen, die während dieses Profil verwendet werden können.</span><span class="sxs-lookup"><span data-stu-id="0aa31-101">The number of instances that can be used during this profile.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ScaleCapacity ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Monitor.Management.Models.ScaleCapacity.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Monitor</AssemblyName>
        <AssemblyVersion>0.18.0.0</AssemblyVersion>
        <AssemblyVersion>0.18.1.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="0aa31-102">Initialisiert eine neue Instanz der ScaleCapacity-Klasse.</span><span class="sxs-lookup"><span data-stu-id="0aa31-102">Initializes a new instance of the ScaleCapacity class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ScaleCapacity (string minimum, string maximum, string defaultProperty);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string minimum, string maximum, string defaultProperty) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Monitor.Management.Models.ScaleCapacity.#ctor(System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (minimum As String, maximum As String, defaultProperty As String)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.Monitor.Management.Models.ScaleCapacity : string * string * string -&gt; Microsoft.Azure.Management.Monitor.Management.Models.ScaleCapacity" Usage="new Microsoft.Azure.Management.Monitor.Management.Models.ScaleCapacity (minimum, maximum, defaultProperty)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Monitor</AssemblyName>
        <AssemblyVersion>0.18.0.0</AssemblyVersion>
        <AssemblyVersion>0.18.1.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="minimum" Type="System.String" />
        <Parameter Name="maximum" Type="System.String" />
        <Parameter Name="defaultProperty" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="minimum"><span data-ttu-id="0aa31-103">die Mindestanzahl der Instanzen für die Ressource.</span><span class="sxs-lookup"><span data-stu-id="0aa31-103">the minimum number of instances for the resource.</span></span></param>
        <param name="maximum"><span data-ttu-id="0aa31-104">die maximale Anzahl der Instanzen für die Ressource.</span><span class="sxs-lookup"><span data-stu-id="0aa31-104">the maximum number of instances for the resource.</span></span> <span data-ttu-id="0aa31-105">Die tatsächliche maximale Anzahl der Instanzen wird durch die Kerne beschränkt, die im Abonnement verfügbar sind.</span><span class="sxs-lookup"><span data-stu-id="0aa31-105">The actual maximum number of instances is limited by the cores that are available in the subscription.</span></span></param>
        <param name="defaultProperty"><span data-ttu-id="0aa31-106">die Anzahl der Instanzen, die festgelegt wird, wenn Metriken nicht für die Auswertung verfügbar sind.</span><span class="sxs-lookup"><span data-stu-id="0aa31-106">the number of instances that will be set if metrics are not available for evaluation.</span></span> <span data-ttu-id="0aa31-107">Der Standardwert wird nur verwendet, wenn die aktuelle instanzanzahl niedriger als der Standardwert ist.</span><span class="sxs-lookup"><span data-stu-id="0aa31-107">The default is only used if the current instance count is lower than the default.</span></span></param>
        <summary>
            <span data-ttu-id="0aa31-108">Initialisiert eine neue Instanz der ScaleCapacity-Klasse.</span><span class="sxs-lookup"><span data-stu-id="0aa31-108">Initializes a new instance of the ScaleCapacity class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DefaultProperty">
      <MemberSignature Language="C#" Value="public string DefaultProperty { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string DefaultProperty" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Monitor.Management.Models.ScaleCapacity.DefaultProperty" />
      <MemberSignature Language="VB.NET" Value="Public Property DefaultProperty As String" />
      <MemberSignature Language="F#" Value="member this.DefaultProperty : string with get, set" Usage="Microsoft.Azure.Management.Monitor.Management.Models.ScaleCapacity.DefaultProperty" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Monitor</AssemblyName>
        <AssemblyVersion>0.18.0.0</AssemblyVersion>
        <AssemblyVersion>0.18.1.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="default")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="0aa31-109">Ruft ab oder legt die Anzahl der Instanzen, die festgelegt wird, wenn Metriken nicht für die Auswertung verfügbar sind.</span><span class="sxs-lookup"><span data-stu-id="0aa31-109">Gets or sets the number of instances that will be set if metrics are not available for evaluation.</span></span> <span data-ttu-id="0aa31-110">Der Standardwert wird nur verwendet, wenn die aktuelle instanzanzahl niedriger als der Standardwert ist.</span><span class="sxs-lookup"><span data-stu-id="0aa31-110">The default is only used if the current instance count is lower than the default.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Maximum">
      <MemberSignature Language="C#" Value="public string Maximum { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Maximum" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Monitor.Management.Models.ScaleCapacity.Maximum" />
      <MemberSignature Language="VB.NET" Value="Public Property Maximum As String" />
      <MemberSignature Language="F#" Value="member this.Maximum : string with get, set" Usage="Microsoft.Azure.Management.Monitor.Management.Models.ScaleCapacity.Maximum" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Monitor</AssemblyName>
        <AssemblyVersion>0.18.0.0</AssemblyVersion>
        <AssemblyVersion>0.18.1.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="maximum")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="0aa31-111">Ruft ab oder legt die maximale Anzahl der Instanzen für die Ressource.</span><span class="sxs-lookup"><span data-stu-id="0aa31-111">Gets or sets the maximum number of instances for the resource.</span></span> <span data-ttu-id="0aa31-112">Die tatsächliche maximale Anzahl der Instanzen wird durch die Kerne beschränkt, die im Abonnement verfügbar sind.</span><span class="sxs-lookup"><span data-stu-id="0aa31-112">The actual maximum number of instances is limited by the cores that are available in the subscription.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Minimum">
      <MemberSignature Language="C#" Value="public string Minimum { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Minimum" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Monitor.Management.Models.ScaleCapacity.Minimum" />
      <MemberSignature Language="VB.NET" Value="Public Property Minimum As String" />
      <MemberSignature Language="F#" Value="member this.Minimum : string with get, set" Usage="Microsoft.Azure.Management.Monitor.Management.Models.ScaleCapacity.Minimum" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Monitor</AssemblyName>
        <AssemblyVersion>0.18.0.0</AssemblyVersion>
        <AssemblyVersion>0.18.1.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="minimum")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="0aa31-113">Ruft ab oder legt die Mindestanzahl der Instanzen für die Ressource fest.</span><span class="sxs-lookup"><span data-stu-id="0aa31-113">Gets or sets the minimum number of instances for the resource.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Validate">
      <MemberSignature Language="C#" Value="public virtual void Validate ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Validate() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Monitor.Management.Models.ScaleCapacity.Validate" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Sub Validate ()" />
      <MemberSignature Language="F#" Value="abstract member Validate : unit -&gt; unit&#xA;override this.Validate : unit -&gt; unit" Usage="scaleCapacity.Validate " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Monitor</AssemblyName>
        <AssemblyVersion>0.18.0.0</AssemblyVersion>
        <AssemblyVersion>0.18.1.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="0aa31-114">Überprüfen Sie das Objekt.</span><span class="sxs-lookup"><span data-stu-id="0aa31-114">Validate the object.</span></span>
            </summary>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="0aa31-115">Wird ausgelöst, wenn die Validierung fehlschlägt</span><span class="sxs-lookup"><span data-stu-id="0aa31-115">Thrown if validation fails</span></span>
            </exception>
      </Docs>
    </Member>
  </Members>
</Type>