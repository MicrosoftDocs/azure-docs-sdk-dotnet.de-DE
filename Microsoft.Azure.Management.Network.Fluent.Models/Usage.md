<Type Name="Usage" FullName="Microsoft.Azure.Management.Network.Fluent.Models.Usage">
  <TypeSignature Language="C#" Value="public class Usage" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi Usage extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Network.Fluent.Models.Usage" />
  <TypeSignature Language="VB.NET" Value="Public Class Usage" />
  <TypeSignature Language="F#" Value="type Usage = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="d6249-101">Beschreibt die Netzwerkverwendung für die Ressource.</span><span class="sxs-lookup"><span data-stu-id="d6249-101">Describes network resource usage.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public Usage ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.Models.Usage.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="d6249-102">Initialisiert eine neue Instanz der Klasse Verwendung an.</span><span class="sxs-lookup"><span data-stu-id="d6249-102">Initializes a new instance of the Usage class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public Usage (long currentValue, long limit, Microsoft.Azure.Management.Network.Fluent.Models.UsageName name);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(int64 currentValue, int64 limit, class Microsoft.Azure.Management.Network.Fluent.Models.UsageName name) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.Models.Usage.#ctor(System.Int64,System.Int64,Microsoft.Azure.Management.Network.Fluent.Models.UsageName)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (currentValue As Long, limit As Long, name As UsageName)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.Network.Fluent.Models.Usage : int64 * int64 * Microsoft.Azure.Management.Network.Fluent.Models.UsageName -&gt; Microsoft.Azure.Management.Network.Fluent.Models.Usage" Usage="new Microsoft.Azure.Management.Network.Fluent.Models.Usage (currentValue, limit, name)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="currentValue" Type="System.Int64" />
        <Parameter Name="limit" Type="System.Int64" />
        <Parameter Name="name" Type="Microsoft.Azure.Management.Network.Fluent.Models.UsageName" />
      </Parameters>
      <Docs>
        <param name="currentValue"><span data-ttu-id="d6249-103">Der aktuelle Wert der Verwendung.</span><span class="sxs-lookup"><span data-stu-id="d6249-103">The current value of the usage.</span></span></param>
        <param name="limit"><span data-ttu-id="d6249-104">Die Grenze der Nutzung.</span><span class="sxs-lookup"><span data-stu-id="d6249-104">The limit of usage.</span></span></param>
        <param name="name"><span data-ttu-id="d6249-105">Der Name des Typs der Nutzung.</span><span class="sxs-lookup"><span data-stu-id="d6249-105">The name of the type of usage.</span></span></param>
        <summary>
            <span data-ttu-id="d6249-106">Initialisiert eine neue Instanz der Klasse Verwendung an.</span><span class="sxs-lookup"><span data-stu-id="d6249-106">Initializes a new instance of the Usage class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CurrentValue">
      <MemberSignature Language="C#" Value="public long CurrentValue { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int64 CurrentValue" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Fluent.Models.Usage.CurrentValue" />
      <MemberSignature Language="VB.NET" Value="Public Property CurrentValue As Long" />
      <MemberSignature Language="F#" Value="member this.CurrentValue : int64 with get, set" Usage="Microsoft.Azure.Management.Network.Fluent.Models.Usage.CurrentValue" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="currentValue")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Int64</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="d6249-107">Ruft ab oder legt den aktuellen Wert der Verwendung.</span><span class="sxs-lookup"><span data-stu-id="d6249-107">Gets or sets the current value of the usage.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Limit">
      <MemberSignature Language="C#" Value="public long Limit { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int64 Limit" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Fluent.Models.Usage.Limit" />
      <MemberSignature Language="VB.NET" Value="Public Property Limit As Long" />
      <MemberSignature Language="F#" Value="member this.Limit : int64 with get, set" Usage="Microsoft.Azure.Management.Network.Fluent.Models.Usage.Limit" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="limit")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Int64</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="d6249-108">Ruft ab oder legt das Limit der Nutzung.</span><span class="sxs-lookup"><span data-stu-id="d6249-108">Gets or sets the limit of usage.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Name">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Network.Fluent.Models.UsageName Name { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.Network.Fluent.Models.UsageName Name" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Fluent.Models.Usage.Name" />
      <MemberSignature Language="VB.NET" Value="Public Property Name As UsageName" />
      <MemberSignature Language="F#" Value="member this.Name : Microsoft.Azure.Management.Network.Fluent.Models.UsageName with get, set" Usage="Microsoft.Azure.Management.Network.Fluent.Models.Usage.Name" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="name")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Network.Fluent.Models.UsageName</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="d6249-109">Ruft ab oder legt den Namen des Typs der Nutzung.</span><span class="sxs-lookup"><span data-stu-id="d6249-109">Gets or sets the name of the type of usage.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Unit">
      <MemberSignature Language="C#" Value="public static string Unit { get; }" />
      <MemberSignature Language="ILAsm" Value=".property string Unit" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Fluent.Models.Usage.Unit" />
      <MemberSignature Language="VB.NET" Value="Public Shared ReadOnly Property Unit As String" />
      <MemberSignature Language="F#" Value="member this.Unit : string" Usage="Microsoft.Azure.Management.Network.Fluent.Models.Usage.Unit" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="unit")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="d6249-110">Eine Enumeration, die die Maßeinheit beschreibt.</span><span class="sxs-lookup"><span data-stu-id="d6249-110">An enum describing the unit of measurement.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Validate">
      <MemberSignature Language="C#" Value="public virtual void Validate ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Validate() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.Models.Usage.Validate" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Sub Validate ()" />
      <MemberSignature Language="F#" Value="abstract member Validate : unit -&gt; unit&#xA;override this.Validate : unit -&gt; unit" Usage="usage.Validate " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="d6249-111">Überprüfen Sie das Objekt.</span><span class="sxs-lookup"><span data-stu-id="d6249-111">Validate the object.</span></span>
            </summary>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="d6249-112">Wird ausgelöst, wenn die Validierung fehlschlägt</span><span class="sxs-lookup"><span data-stu-id="d6249-112">Thrown if validation fails</span></span>
            </exception>
      </Docs>
    </Member>
  </Members>
</Type>