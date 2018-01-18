<Type Name="MxRecord" FullName="Microsoft.Azure.Management.Dns.Models.MxRecord">
  <TypeSignature Language="C#" Value="public class MxRecord" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit MxRecord extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Dns.Models.MxRecord" />
  <TypeSignature Language="VB.NET" Value="Public Class MxRecord" />
  <TypeSignature Language="F#" Value="type MxRecord = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Dns</AssemblyName>
    <AssemblyVersion>1.0.0.0</AssemblyVersion>
    <AssemblyVersion>2.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="2c785-101">Einen MX-Eintrag.</span><span class="sxs-lookup"><span data-stu-id="2c785-101">An MX record.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public MxRecord ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Dns.Models.MxRecord.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Dns</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="2c785-102">Initialisiert eine neue Instanz der MxRecord-Klasse.</span><span class="sxs-lookup"><span data-stu-id="2c785-102">Initializes a new instance of the MxRecord class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public MxRecord (Nullable&lt;int&gt; preference = null, string exchange = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(valuetype System.Nullable`1&lt;int32&gt; preference, string exchange) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Dns.Models.MxRecord.#ctor(System.Nullable{System.Int32},System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional preference As Nullable(Of Integer) = null, Optional exchange As String = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.Dns.Models.MxRecord : Nullable&lt;int&gt; * string -&gt; Microsoft.Azure.Management.Dns.Models.MxRecord" Usage="new Microsoft.Azure.Management.Dns.Models.MxRecord (preference, exchange)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Dns</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="preference" Type="System.Nullable&lt;System.Int32&gt;" />
        <Parameter Name="exchange" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="preference"><span data-ttu-id="2c785-103">Der Einstellungswert für dieser MX-Eintrag.</span><span class="sxs-lookup"><span data-stu-id="2c785-103">The preference value for this MX record.</span></span></param>
        <param name="exchange"><span data-ttu-id="2c785-104">Der Domänenname des e-Mail-Hosts für diesen MX-Datensatz.</span><span class="sxs-lookup"><span data-stu-id="2c785-104">The domain name of the mail host for this MX record.</span></span></param>
        <summary>
            <span data-ttu-id="2c785-105">Initialisiert eine neue Instanz der MxRecord-Klasse.</span><span class="sxs-lookup"><span data-stu-id="2c785-105">Initializes a new instance of the MxRecord class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Exchange">
      <MemberSignature Language="C#" Value="public string Exchange { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Exchange" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Dns.Models.MxRecord.Exchange" />
      <MemberSignature Language="VB.NET" Value="Public Property Exchange As String" />
      <MemberSignature Language="F#" Value="member this.Exchange : string with get, set" Usage="Microsoft.Azure.Management.Dns.Models.MxRecord.Exchange" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Dns</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="exchange")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="2c785-106">Ruft ab oder legt den Domänennamen des e-Mail-Hosts für diesen MX-Datensatz.</span><span class="sxs-lookup"><span data-stu-id="2c785-106">Gets or sets the domain name of the mail host for this MX record.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Preference">
      <MemberSignature Language="C#" Value="public Nullable&lt;int&gt; Preference { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int32&gt; Preference" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Dns.Models.MxRecord.Preference" />
      <MemberSignature Language="VB.NET" Value="Public Property Preference As Nullable(Of Integer)" />
      <MemberSignature Language="F#" Value="member this.Preference : Nullable&lt;int&gt; with get, set" Usage="Microsoft.Azure.Management.Dns.Models.MxRecord.Preference" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Dns</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="preference")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Int32&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="2c785-107">Ruft ab oder legt den Einstellungswert für diese MX-Eintrag.</span><span class="sxs-lookup"><span data-stu-id="2c785-107">Gets or sets the preference value for this MX record.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>