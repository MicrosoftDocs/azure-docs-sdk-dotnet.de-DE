<Type Name="ManagedIntegrationRuntimeError" FullName="Microsoft.Azure.Management.DataFactory.Models.ManagedIntegrationRuntimeError">
  <TypeSignature Language="C#" Value="public class ManagedIntegrationRuntimeError" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit ManagedIntegrationRuntimeError extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.DataFactory.Models.ManagedIntegrationRuntimeError" />
  <TypeSignature Language="VB.NET" Value="Public Class ManagedIntegrationRuntimeError" />
  <TypeSignature Language="F#" Value="type ManagedIntegrationRuntimeError = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
    <AssemblyVersion>0.2.0.0</AssemblyVersion>
    <AssemblyVersion>0.3.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="4b5e3-101">Fehler-Definition für verwaltete integrationslaufzeit.</span><span class="sxs-lookup"><span data-stu-id="4b5e3-101">Error definition for managed integration runtime.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ManagedIntegrationRuntimeError ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactory.Models.ManagedIntegrationRuntimeError.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.2.0.0</AssemblyVersion>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="4b5e3-102">Initialisiert eine neue Instanz der ManagedIntegrationRuntimeError-Klasse.</span><span class="sxs-lookup"><span data-stu-id="4b5e3-102">Initializes a new instance of the ManagedIntegrationRuntimeError class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ManagedIntegrationRuntimeError (Nullable&lt;DateTime&gt; time = null, string code = null, System.Collections.Generic.IList&lt;string&gt; parameters = null, string message = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; time, string code, class System.Collections.Generic.IList`1&lt;string&gt; parameters, string message) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactory.Models.ManagedIntegrationRuntimeError.#ctor(System.Nullable{System.DateTime},System.String,System.Collections.Generic.IList{System.String},System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional time As Nullable(Of DateTime) = null, Optional code As String = null, Optional parameters As IList(Of String) = null, Optional message As String = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.DataFactory.Models.ManagedIntegrationRuntimeError : Nullable&lt;DateTime&gt; * string * System.Collections.Generic.IList&lt;string&gt; * string -&gt; Microsoft.Azure.Management.DataFactory.Models.ManagedIntegrationRuntimeError" Usage="new Microsoft.Azure.Management.DataFactory.Models.ManagedIntegrationRuntimeError (time, code, parameters, message)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.2.0.0</AssemblyVersion>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="time" Type="System.Nullable&lt;System.DateTime&gt;" />
        <Parameter Name="code" Type="System.String" />
        <Parameter Name="parameters" Type="System.Collections.Generic.IList&lt;System.String&gt;" />
        <Parameter Name="message" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="time"><span data-ttu-id="4b5e3-103">Der Zeitpunkt, wann der Fehler aufgetreten ist.</span><span class="sxs-lookup"><span data-stu-id="4b5e3-103">The time when the error occurred.</span></span></param>
        <param name="code"><span data-ttu-id="4b5e3-104">Fehlercode</span><span class="sxs-lookup"><span data-stu-id="4b5e3-104">Error code.</span></span></param>
        <param name="parameters"><span data-ttu-id="4b5e3-105">Fehler Laufzeitparameter verwaltete Integration.</span><span class="sxs-lookup"><span data-stu-id="4b5e3-105">Managed integration runtime error parameters.</span></span></param>
        <param name="message"><span data-ttu-id="4b5e3-106">Fehlermeldung.</span><span class="sxs-lookup"><span data-stu-id="4b5e3-106">Error message.</span></span></param>
        <summary>
            <span data-ttu-id="4b5e3-107">Initialisiert eine neue Instanz der ManagedIntegrationRuntimeError-Klasse.</span><span class="sxs-lookup"><span data-stu-id="4b5e3-107">Initializes a new instance of the ManagedIntegrationRuntimeError class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Code">
      <MemberSignature Language="C#" Value="public string Code { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Code" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactory.Models.ManagedIntegrationRuntimeError.Code" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Code As String" />
      <MemberSignature Language="F#" Value="member this.Code : string" Usage="Microsoft.Azure.Management.DataFactory.Models.ManagedIntegrationRuntimeError.Code" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.2.0.0</AssemblyVersion>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="code")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="4b5e3-108">Ruft den Fehlercode ab.</span><span class="sxs-lookup"><span data-stu-id="4b5e3-108">Gets error code.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Message">
      <MemberSignature Language="C#" Value="public string Message { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Message" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactory.Models.ManagedIntegrationRuntimeError.Message" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Message As String" />
      <MemberSignature Language="F#" Value="member this.Message : string" Usage="Microsoft.Azure.Management.DataFactory.Models.ManagedIntegrationRuntimeError.Message" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.2.0.0</AssemblyVersion>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="message")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="4b5e3-109">Ruft die Fehlermeldung ab.</span><span class="sxs-lookup"><span data-stu-id="4b5e3-109">Gets error message.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Parameters">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;string&gt; Parameters { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;string&gt; Parameters" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactory.Models.ManagedIntegrationRuntimeError.Parameters" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Parameters As IList(Of String)" />
      <MemberSignature Language="F#" Value="member this.Parameters : System.Collections.Generic.IList&lt;string&gt;" Usage="Microsoft.Azure.Management.DataFactory.Models.ManagedIntegrationRuntimeError.Parameters" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.2.0.0</AssemblyVersion>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="parameters")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;System.String&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="4b5e3-110">Ruft verwaltet Integration Laufzeitparameter-Fehler.</span><span class="sxs-lookup"><span data-stu-id="4b5e3-110">Gets managed integration runtime error parameters.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Time">
      <MemberSignature Language="C#" Value="public Nullable&lt;DateTime&gt; Time { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; Time" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactory.Models.ManagedIntegrationRuntimeError.Time" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Time As Nullable(Of DateTime)" />
      <MemberSignature Language="F#" Value="member this.Time : Nullable&lt;DateTime&gt;" Usage="Microsoft.Azure.Management.DataFactory.Models.ManagedIntegrationRuntimeError.Time" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.2.0.0</AssemblyVersion>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="time")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.DateTime&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="4b5e3-111">Ruft den Zeitpunkt des Auftretens des Fehlers.</span><span class="sxs-lookup"><span data-stu-id="4b5e3-111">Gets the time when the error occurred.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>