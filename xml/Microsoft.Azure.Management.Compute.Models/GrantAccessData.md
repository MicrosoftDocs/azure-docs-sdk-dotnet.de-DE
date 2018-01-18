<Type Name="GrantAccessData" FullName="Microsoft.Azure.Management.Compute.Models.GrantAccessData">
  <TypeSignature Language="C#" Value="public class GrantAccessData" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit GrantAccessData extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Compute.Models.GrantAccessData" />
  <TypeSignature Language="VB.NET" Value="Public Class GrantAccessData" />
  <TypeSignature Language="F#" Value="type GrantAccessData = class" />
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
            <span data-ttu-id="a808d-101">Daten, die für die Anforderung eine SAS.</span><span class="sxs-lookup"><span data-stu-id="a808d-101">Data used for requesting a SAS.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public GrantAccessData ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Models.GrantAccessData.#ctor" />
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
            <span data-ttu-id="a808d-102">Initialisiert eine neue Instanz der GrantAccessData-Klasse.</span><span class="sxs-lookup"><span data-stu-id="a808d-102">Initializes a new instance of the GrantAccessData class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public GrantAccessData (Microsoft.Azure.Management.Compute.Models.AccessLevel access, int durationInSeconds);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(valuetype Microsoft.Azure.Management.Compute.Models.AccessLevel access, int32 durationInSeconds) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Models.GrantAccessData.#ctor(Microsoft.Azure.Management.Compute.Models.AccessLevel,System.Int32)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (access As AccessLevel, durationInSeconds As Integer)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.Compute.Models.GrantAccessData : Microsoft.Azure.Management.Compute.Models.AccessLevel * int -&gt; Microsoft.Azure.Management.Compute.Models.GrantAccessData" Usage="new Microsoft.Azure.Management.Compute.Models.GrantAccessData (access, durationInSeconds)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="access" Type="Microsoft.Azure.Management.Compute.Models.AccessLevel" />
        <Parameter Name="durationInSeconds" Type="System.Int32" />
      </Parameters>
      <Docs>
        <param name="access"><span data-ttu-id="a808d-103">Folgende Werte sind möglich: 'None', 'Read'</span><span class="sxs-lookup"><span data-stu-id="a808d-103">Possible values include: 'None', 'Read'</span></span></param>
        <param name="durationInSeconds"><span data-ttu-id="a808d-104">Die Zeitdauer in Sekunden, bis der SAS-Zugriff läuft ab.</span><span class="sxs-lookup"><span data-stu-id="a808d-104">Time duration in seconds until the SAS access expires.</span></span></param>
        <summary>
            <span data-ttu-id="a808d-105">Initialisiert eine neue Instanz der GrantAccessData-Klasse.</span><span class="sxs-lookup"><span data-stu-id="a808d-105">Initializes a new instance of the GrantAccessData class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Access">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Compute.Models.AccessLevel Access { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype Microsoft.Azure.Management.Compute.Models.AccessLevel Access" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Compute.Models.GrantAccessData.Access" />
      <MemberSignature Language="VB.NET" Value="Public Property Access As AccessLevel" />
      <MemberSignature Language="F#" Value="member this.Access : Microsoft.Azure.Management.Compute.Models.AccessLevel with get, set" Usage="Microsoft.Azure.Management.Compute.Models.GrantAccessData.Access" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="access")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Compute.Models.AccessLevel</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="a808d-106">Ruft ab oder legt folgende Werte möglich sind: 'None', 'Read'</span><span class="sxs-lookup"><span data-stu-id="a808d-106">Gets or sets possible values include: 'None', 'Read'</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DurationInSeconds">
      <MemberSignature Language="C#" Value="public int DurationInSeconds { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int32 DurationInSeconds" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Compute.Models.GrantAccessData.DurationInSeconds" />
      <MemberSignature Language="VB.NET" Value="Public Property DurationInSeconds As Integer" />
      <MemberSignature Language="F#" Value="member this.DurationInSeconds : int with get, set" Usage="Microsoft.Azure.Management.Compute.Models.GrantAccessData.DurationInSeconds" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="durationInSeconds")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Int32</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="a808d-107">Ruft ab oder legt die Dauer in Sekunden bis zum Ablauf des SAS-Zugriffs fest.</span><span class="sxs-lookup"><span data-stu-id="a808d-107">Gets or sets time duration in seconds until the SAS access expires.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Validate">
      <MemberSignature Language="C#" Value="public virtual void Validate ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Validate() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Models.GrantAccessData.Validate" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Sub Validate ()" />
      <MemberSignature Language="F#" Value="abstract member Validate : unit -&gt; unit&#xA;override this.Validate : unit -&gt; unit" Usage="grantAccessData.Validate " />
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
            <span data-ttu-id="a808d-108">Überprüfen Sie das Objekt.</span><span class="sxs-lookup"><span data-stu-id="a808d-108">Validate the object.</span></span>
            </summary>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="a808d-109">Wird ausgelöst, wenn die Validierung fehlschlägt</span><span class="sxs-lookup"><span data-stu-id="a808d-109">Thrown if validation fails</span></span>
            </exception>
      </Docs>
    </Member>
  </Members>
</Type>