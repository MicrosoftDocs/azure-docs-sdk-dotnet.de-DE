<Type Name="AlertErrorDetails" FullName="Microsoft.Azure.Management.StorSimple8000Series.Models.AlertErrorDetails">
  <TypeSignature Language="C#" Value="public class AlertErrorDetails" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit AlertErrorDetails extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.StorSimple8000Series.Models.AlertErrorDetails" />
  <TypeSignature Language="VB.NET" Value="Public Class AlertErrorDetails" />
  <TypeSignature Language="F#" Value="type AlertErrorDetails = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
    <AssemblyVersion>1.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="d5928-101">Die Details des Fehlers für die die Warnung ausgelöst wurde</span><span class="sxs-lookup"><span data-stu-id="d5928-101">The details of the error for which the alert was raised</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public AlertErrorDetails ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StorSimple8000Series.Models.AlertErrorDetails.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="d5928-102">Initialisiert eine neue Instanz der AlertErrorDetails-Klasse.</span><span class="sxs-lookup"><span data-stu-id="d5928-102">Initializes a new instance of the AlertErrorDetails class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public AlertErrorDetails (string errorCode = null, string errorMessage = null, Nullable&lt;int&gt; occurences = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string errorCode, string errorMessage, valuetype System.Nullable`1&lt;int32&gt; occurences) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StorSimple8000Series.Models.AlertErrorDetails.#ctor(System.String,System.String,System.Nullable{System.Int32})" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional errorCode As String = null, Optional errorMessage As String = null, Optional occurences As Nullable(Of Integer) = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.StorSimple8000Series.Models.AlertErrorDetails : string * string * Nullable&lt;int&gt; -&gt; Microsoft.Azure.Management.StorSimple8000Series.Models.AlertErrorDetails" Usage="new Microsoft.Azure.Management.StorSimple8000Series.Models.AlertErrorDetails (errorCode, errorMessage, occurences)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="errorCode" Type="System.String" />
        <Parameter Name="errorMessage" Type="System.String" />
        <Parameter Name="occurences" Type="System.Nullable&lt;System.Int32&gt;" />
      </Parameters>
      <Docs>
        <param name="errorCode"><span data-ttu-id="d5928-103">Der Fehlercode</span><span class="sxs-lookup"><span data-stu-id="d5928-103">The error code</span></span></param>
        <param name="errorMessage"><span data-ttu-id="d5928-104">Die Fehlermeldung</span><span class="sxs-lookup"><span data-stu-id="d5928-104">The error message</span></span></param>
        <param name="occurences"><span data-ttu-id="d5928-105">Die Anzahl der Vorkommnisse</span><span class="sxs-lookup"><span data-stu-id="d5928-105">The number of occurences</span></span></param>
        <summary>
            <span data-ttu-id="d5928-106">Initialisiert eine neue Instanz der AlertErrorDetails-Klasse.</span><span class="sxs-lookup"><span data-stu-id="d5928-106">Initializes a new instance of the AlertErrorDetails class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ErrorCode">
      <MemberSignature Language="C#" Value="public string ErrorCode { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ErrorCode" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.StorSimple8000Series.Models.AlertErrorDetails.ErrorCode" />
      <MemberSignature Language="VB.NET" Value="Public Property ErrorCode As String" />
      <MemberSignature Language="F#" Value="member this.ErrorCode : string with get, set" Usage="Microsoft.Azure.Management.StorSimple8000Series.Models.AlertErrorDetails.ErrorCode" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="errorCode")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="d5928-107">Ruft ab oder legt den Fehlercode</span><span class="sxs-lookup"><span data-stu-id="d5928-107">Gets or sets the error code</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ErrorMessage">
      <MemberSignature Language="C#" Value="public string ErrorMessage { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ErrorMessage" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.StorSimple8000Series.Models.AlertErrorDetails.ErrorMessage" />
      <MemberSignature Language="VB.NET" Value="Public Property ErrorMessage As String" />
      <MemberSignature Language="F#" Value="member this.ErrorMessage : string with get, set" Usage="Microsoft.Azure.Management.StorSimple8000Series.Models.AlertErrorDetails.ErrorMessage" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="errorMessage")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="d5928-108">Ruft ab oder legt die Fehlermeldung</span><span class="sxs-lookup"><span data-stu-id="d5928-108">Gets or sets the error message</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Occurences">
      <MemberSignature Language="C#" Value="public Nullable&lt;int&gt; Occurences { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int32&gt; Occurences" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.StorSimple8000Series.Models.AlertErrorDetails.Occurences" />
      <MemberSignature Language="VB.NET" Value="Public Property Occurences As Nullable(Of Integer)" />
      <MemberSignature Language="F#" Value="member this.Occurences : Nullable&lt;int&gt; with get, set" Usage="Microsoft.Azure.Management.StorSimple8000Series.Models.AlertErrorDetails.Occurences" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="occurences")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Int32&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="d5928-109">Ruft ab oder legt die Anzahl der Vorkommnisse</span><span class="sxs-lookup"><span data-stu-id="d5928-109">Gets or sets the number of occurences</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>