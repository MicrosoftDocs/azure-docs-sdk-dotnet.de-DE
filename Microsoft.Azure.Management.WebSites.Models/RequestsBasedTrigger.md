<Type Name="RequestsBasedTrigger" FullName="Microsoft.Azure.Management.WebSites.Models.RequestsBasedTrigger">
  <TypeSignature Language="C#" Value="public class RequestsBasedTrigger" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit RequestsBasedTrigger extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.WebSites.Models.RequestsBasedTrigger" />
  <TypeSignature Language="VB.NET" Value="Public Class RequestsBasedTrigger" />
  <TypeSignature Language="F#" Value="type RequestsBasedTrigger = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
    <AssemblyVersion>1.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="ce877-101">Trigger, die basierend auf die Gesamtzahl der Anforderungen.</span><span class="sxs-lookup"><span data-stu-id="ce877-101">Trigger based on total requests.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public RequestsBasedTrigger ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.WebSites.Models.RequestsBasedTrigger.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="ce877-102">Initialisiert eine neue Instanz der RequestsBasedTrigger-Klasse.</span><span class="sxs-lookup"><span data-stu-id="ce877-102">Initializes a new instance of the RequestsBasedTrigger class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public RequestsBasedTrigger (Nullable&lt;int&gt; count = null, string timeInterval = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(valuetype System.Nullable`1&lt;int32&gt; count, string timeInterval) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.WebSites.Models.RequestsBasedTrigger.#ctor(System.Nullable{System.Int32},System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional count As Nullable(Of Integer) = null, Optional timeInterval As String = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.WebSites.Models.RequestsBasedTrigger : Nullable&lt;int&gt; * string -&gt; Microsoft.Azure.Management.WebSites.Models.RequestsBasedTrigger" Usage="new Microsoft.Azure.Management.WebSites.Models.RequestsBasedTrigger (count, timeInterval)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="count" Type="System.Nullable&lt;System.Int32&gt;" />
        <Parameter Name="timeInterval" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="count"><span data-ttu-id="ce877-103">Die Anzahl.</span><span class="sxs-lookup"><span data-stu-id="ce877-103">Count.</span></span></param>
        <param name="timeInterval"><span data-ttu-id="ce877-104">Zeitintervall.</span><span class="sxs-lookup"><span data-stu-id="ce877-104">Time interval.</span></span></param>
        <summary>
            <span data-ttu-id="ce877-105">Initialisiert eine neue Instanz der RequestsBasedTrigger-Klasse.</span><span class="sxs-lookup"><span data-stu-id="ce877-105">Initializes a new instance of the RequestsBasedTrigger class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Count">
      <MemberSignature Language="C#" Value="public Nullable&lt;int&gt; Count { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int32&gt; Count" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.RequestsBasedTrigger.Count" />
      <MemberSignature Language="VB.NET" Value="Public Property Count As Nullable(Of Integer)" />
      <MemberSignature Language="F#" Value="member this.Count : Nullable&lt;int&gt; with get, set" Usage="Microsoft.Azure.Management.WebSites.Models.RequestsBasedTrigger.Count" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="count")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Int32&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="ce877-106">Ruft ab oder legt die Anzahl.</span><span class="sxs-lookup"><span data-stu-id="ce877-106">Gets or sets count.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="TimeInterval">
      <MemberSignature Language="C#" Value="public string TimeInterval { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string TimeInterval" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.RequestsBasedTrigger.TimeInterval" />
      <MemberSignature Language="VB.NET" Value="Public Property TimeInterval As String" />
      <MemberSignature Language="F#" Value="member this.TimeInterval : string with get, set" Usage="Microsoft.Azure.Management.WebSites.Models.RequestsBasedTrigger.TimeInterval" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="timeInterval")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="ce877-107">Ruft ab oder legt das Zeitintervall fest.</span><span class="sxs-lookup"><span data-stu-id="ce877-107">Gets or sets time interval.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>