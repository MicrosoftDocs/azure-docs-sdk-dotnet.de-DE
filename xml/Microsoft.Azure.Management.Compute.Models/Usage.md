<Type Name="Usage" FullName="Microsoft.Azure.Management.Compute.Models.Usage">
  <TypeSignature Language="C#" Value="public class Usage" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi Usage extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Compute.Models.Usage" />
  <TypeSignature Language="VB.NET" Value="Public Class Usage" />
  <TypeSignature Language="F#" Value="type Usage = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
    <AssemblyVersion>16.0.0.0</AssemblyVersion>
    <AssemblyVersion>17.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="a30b4-101">Beschreibt die Compute-Ressourcenverwendung.</span><span class="sxs-lookup"><span data-stu-id="a30b4-101">Describes Compute Resource Usage.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public Usage ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Models.Usage.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="a30b4-102">Initialisiert eine neue Instanz der Klasse Verwendung an.</span><span class="sxs-lookup"><span data-stu-id="a30b4-102">Initializes a new instance of the Usage class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public Usage (int currentValue, long limit, Microsoft.Azure.Management.Compute.Models.UsageName name);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(int32 currentValue, int64 limit, class Microsoft.Azure.Management.Compute.Models.UsageName name) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Models.Usage.#ctor(System.Int32,System.Int64,Microsoft.Azure.Management.Compute.Models.UsageName)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (currentValue As Integer, limit As Long, name As UsageName)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.Compute.Models.Usage : int * int64 * Microsoft.Azure.Management.Compute.Models.UsageName -&gt; Microsoft.Azure.Management.Compute.Models.Usage" Usage="new Microsoft.Azure.Management.Compute.Models.Usage (currentValue, limit, name)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="currentValue" Type="System.Int32" />
        <Parameter Name="limit" Type="System.Int64" />
        <Parameter Name="name" Type="Microsoft.Azure.Management.Compute.Models.UsageName" />
      </Parameters>
      <Docs>
        <param name="currentValue"><span data-ttu-id="a30b4-103">Die aktuelle Verwendung der Ressource.</span><span class="sxs-lookup"><span data-stu-id="a30b4-103">The current usage of the resource.</span></span></param>
        <param name="limit"><span data-ttu-id="a30b4-104">Der maximal zulässige Verwendung der Ressource.</span><span class="sxs-lookup"><span data-stu-id="a30b4-104">The maximum permitted usage of the resource.</span></span></param>
        <param name="name"><span data-ttu-id="a30b4-105">Der Name des Typs der Nutzung.</span><span class="sxs-lookup"><span data-stu-id="a30b4-105">The name of the type of usage.</span></span></param>
        <summary>
            <span data-ttu-id="a30b4-106">Initialisiert eine neue Instanz der Klasse Verwendung an.</span><span class="sxs-lookup"><span data-stu-id="a30b4-106">Initializes a new instance of the Usage class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CurrentValue">
      <MemberSignature Language="C#" Value="public int CurrentValue { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int32 CurrentValue" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Compute.Models.Usage.CurrentValue" />
      <MemberSignature Language="VB.NET" Value="Public Property CurrentValue As Integer" />
      <MemberSignature Language="F#" Value="member this.CurrentValue : int with get, set" Usage="Microsoft.Azure.Management.Compute.Models.Usage.CurrentValue" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="currentValue")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Int32</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="a30b4-107">Ruft ab oder legt die aktuelle Verwendung der Ressource.</span><span class="sxs-lookup"><span data-stu-id="a30b4-107">Gets or sets the current usage of the resource.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Limit">
      <MemberSignature Language="C#" Value="public long Limit { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int64 Limit" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Compute.Models.Usage.Limit" />
      <MemberSignature Language="VB.NET" Value="Public Property Limit As Long" />
      <MemberSignature Language="F#" Value="member this.Limit : int64 with get, set" Usage="Microsoft.Azure.Management.Compute.Models.Usage.Limit" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
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
            <span data-ttu-id="a30b4-108">Ruft ab oder legt die maximal zulässige Verwendung der Ressource.</span><span class="sxs-lookup"><span data-stu-id="a30b4-108">Gets or sets the maximum permitted usage of the resource.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Name">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Compute.Models.UsageName Name { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.Compute.Models.UsageName Name" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Compute.Models.Usage.Name" />
      <MemberSignature Language="VB.NET" Value="Public Property Name As UsageName" />
      <MemberSignature Language="F#" Value="member this.Name : Microsoft.Azure.Management.Compute.Models.UsageName with get, set" Usage="Microsoft.Azure.Management.Compute.Models.Usage.Name" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="name")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Compute.Models.UsageName</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="a30b4-109">Ruft ab oder legt den Namen des Typs der Nutzung.</span><span class="sxs-lookup"><span data-stu-id="a30b4-109">Gets or sets the name of the type of usage.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Unit">
      <MemberSignature Language="C#" Value="public static string Unit { get; }" />
      <MemberSignature Language="ILAsm" Value=".property string Unit" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Compute.Models.Usage.Unit" />
      <MemberSignature Language="VB.NET" Value="Public Shared ReadOnly Property Unit As String" />
      <MemberSignature Language="F#" Value="member this.Unit : string" Usage="Microsoft.Azure.Management.Compute.Models.Usage.Unit" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
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
            <span data-ttu-id="a30b4-110">Eine Enumeration, die als Maßeinheit für Verwendung beschreibt.</span><span class="sxs-lookup"><span data-stu-id="a30b4-110">An enum describing the unit of usage measurement.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Validate">
      <MemberSignature Language="C#" Value="public virtual void Validate ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Validate() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Models.Usage.Validate" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Sub Validate ()" />
      <MemberSignature Language="F#" Value="abstract member Validate : unit -&gt; unit&#xA;override this.Validate : unit -&gt; unit" Usage="usage.Validate " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="a30b4-111">Überprüfen Sie das Objekt.</span><span class="sxs-lookup"><span data-stu-id="a30b4-111">Validate the object.</span></span>
            </summary>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="a30b4-112">Wird ausgelöst, wenn die Validierung fehlschlägt</span><span class="sxs-lookup"><span data-stu-id="a30b4-112">Thrown if validation fails</span></span>
            </exception>
      </Docs>
    </Member>
  </Members>
</Type>