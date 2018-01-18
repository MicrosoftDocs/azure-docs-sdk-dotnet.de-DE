<Type Name="MabErrorInfo" FullName="Microsoft.Azure.Management.RecoveryServices.Backup.Models.MabErrorInfo">
  <TypeSignature Language="C#" Value="public class MabErrorInfo" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit MabErrorInfo extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.RecoveryServices.Backup.Models.MabErrorInfo" />
  <TypeSignature Language="VB.NET" Value="Public Class MabErrorInfo" />
  <TypeSignature Language="F#" Value="type MabErrorInfo = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.RecoveryServices.Backup</AssemblyName>
    <AssemblyVersion>2.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="dd628-101">MAB spezifische Fehlerinformationen.</span><span class="sxs-lookup"><span data-stu-id="dd628-101">MAB workload-specific error information.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public MabErrorInfo ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.RecoveryServices.Backup.Models.MabErrorInfo.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.RecoveryServices.Backup</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="dd628-102">Initialisiert eine neue Instanz der MabErrorInfo-Klasse.</span><span class="sxs-lookup"><span data-stu-id="dd628-102">Initializes a new instance of the MabErrorInfo class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public MabErrorInfo (string errorString = null, System.Collections.Generic.IList&lt;string&gt; recommendations = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string errorString, class System.Collections.Generic.IList`1&lt;string&gt; recommendations) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.RecoveryServices.Backup.Models.MabErrorInfo.#ctor(System.String,System.Collections.Generic.IList{System.String})" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional errorString As String = null, Optional recommendations As IList(Of String) = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.RecoveryServices.Backup.Models.MabErrorInfo : string * System.Collections.Generic.IList&lt;string&gt; -&gt; Microsoft.Azure.Management.RecoveryServices.Backup.Models.MabErrorInfo" Usage="new Microsoft.Azure.Management.RecoveryServices.Backup.Models.MabErrorInfo (errorString, recommendations)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.RecoveryServices.Backup</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="errorString" Type="System.String" />
        <Parameter Name="recommendations" Type="System.Collections.Generic.IList&lt;System.String&gt;" />
      </Parameters>
      <Docs>
        <param name="errorString"><span data-ttu-id="dd628-103">Lokalisierte fehlermeldungs-Zeichenfolge.</span><span class="sxs-lookup"><span data-stu-id="dd628-103">Localized error string.</span></span></param>
        <param name="recommendations"><span data-ttu-id="dd628-104">Liste der lokalisierten Empfehlungen.</span><span class="sxs-lookup"><span data-stu-id="dd628-104">List of localized recommendations.</span></span></param>
        <summary>
            <span data-ttu-id="dd628-105">Initialisiert eine neue Instanz der MabErrorInfo-Klasse.</span><span class="sxs-lookup"><span data-stu-id="dd628-105">Initializes a new instance of the MabErrorInfo class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ErrorString">
      <MemberSignature Language="C#" Value="public string ErrorString { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ErrorString" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.RecoveryServices.Backup.Models.MabErrorInfo.ErrorString" />
      <MemberSignature Language="VB.NET" Value="Public Property ErrorString As String" />
      <MemberSignature Language="F#" Value="member this.ErrorString : string with get, set" Usage="Microsoft.Azure.Management.RecoveryServices.Backup.Models.MabErrorInfo.ErrorString" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.RecoveryServices.Backup</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="errorString")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="dd628-106">Ruft ab, oder legt ihn fest lokalisierte Fehlerzeichenfolge.</span><span class="sxs-lookup"><span data-stu-id="dd628-106">Gets or sets localized error string.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Recommendations">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;string&gt; Recommendations { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;string&gt; Recommendations" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.RecoveryServices.Backup.Models.MabErrorInfo.Recommendations" />
      <MemberSignature Language="VB.NET" Value="Public Property Recommendations As IList(Of String)" />
      <MemberSignature Language="F#" Value="member this.Recommendations : System.Collections.Generic.IList&lt;string&gt; with get, set" Usage="Microsoft.Azure.Management.RecoveryServices.Backup.Models.MabErrorInfo.Recommendations" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.RecoveryServices.Backup</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="recommendations")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;System.String&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="dd628-107">Ruft ab, oder legt ihn fest lokalisierte Empfehlungen.</span><span class="sxs-lookup"><span data-stu-id="dd628-107">Gets or sets list of localized recommendations.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>