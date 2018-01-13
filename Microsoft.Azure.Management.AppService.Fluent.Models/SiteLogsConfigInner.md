<Type Name="SiteLogsConfigInner" FullName="Microsoft.Azure.Management.AppService.Fluent.Models.SiteLogsConfigInner">
  <TypeSignature Language="C#" Value="public class SiteLogsConfigInner : Microsoft.Azure.Management.AppService.Fluent.Models.ProxyOnlyResource" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit SiteLogsConfigInner extends Microsoft.Azure.Management.AppService.Fluent.Models.ProxyOnlyResource" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.AppService.Fluent.Models.SiteLogsConfigInner" />
  <TypeSignature Language="VB.NET" Value="Public Class SiteLogsConfigInner&#xA;Inherits ProxyOnlyResource" />
  <TypeSignature Language="F#" Value="type SiteLogsConfigInner = class&#xA;    inherit ProxyOnlyResource" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>Microsoft.Azure.Management.ResourceManager.Fluent.Resource</BaseTypeName>
    <BaseTypeName FrameworkAlternate="azure-dotnet">Microsoft.Azure.Management.AppService.Fluent.Models.ProxyOnlyResource</BaseTypeName>
  </Base>
  <Interfaces />
  <Attributes>
    <Attribute>
      <AttributeName>Microsoft.Rest.Serialization.JsonTransformation</AttributeName>
    </Attribute>
  </Attributes>
  <Docs>
    <summary>
            <span data-ttu-id="5bf47-101">Die Konfiguration der App Service-Site-Protokolle.</span><span class="sxs-lookup"><span data-stu-id="5bf47-101">Configuration of App Service site logs.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public SiteLogsConfigInner ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.AppService.Fluent.Models.SiteLogsConfigInner.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="5bf47-102">Initialisiert eine neue Instanz der SiteLogsConfigInner-Klasse.</span><span class="sxs-lookup"><span data-stu-id="5bf47-102">Initializes a new instance of the SiteLogsConfigInner class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public SiteLogsConfigInner (string id = null, string name = null, string kind = null, string type = null, Microsoft.Azure.Management.AppService.Fluent.Models.ApplicationLogsConfig applicationLogs = null, Microsoft.Azure.Management.AppService.Fluent.Models.HttpLogsConfig httpLogs = null, Microsoft.Azure.Management.AppService.Fluent.Models.EnabledConfig failedRequestsTracing = null, Microsoft.Azure.Management.AppService.Fluent.Models.EnabledConfig detailedErrorMessages = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string id, string name, string kind, string type, class Microsoft.Azure.Management.AppService.Fluent.Models.ApplicationLogsConfig applicationLogs, class Microsoft.Azure.Management.AppService.Fluent.Models.HttpLogsConfig httpLogs, class Microsoft.Azure.Management.AppService.Fluent.Models.EnabledConfig failedRequestsTracing, class Microsoft.Azure.Management.AppService.Fluent.Models.EnabledConfig detailedErrorMessages) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.AppService.Fluent.Models.SiteLogsConfigInner.#ctor(System.String,System.String,System.String,System.String,Microsoft.Azure.Management.AppService.Fluent.Models.ApplicationLogsConfig,Microsoft.Azure.Management.AppService.Fluent.Models.HttpLogsConfig,Microsoft.Azure.Management.AppService.Fluent.Models.EnabledConfig,Microsoft.Azure.Management.AppService.Fluent.Models.EnabledConfig)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional id As String = null, Optional name As String = null, Optional kind As String = null, Optional type As String = null, Optional applicationLogs As ApplicationLogsConfig = null, Optional httpLogs As HttpLogsConfig = null, Optional failedRequestsTracing As EnabledConfig = null, Optional detailedErrorMessages As EnabledConfig = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.AppService.Fluent.Models.SiteLogsConfigInner : string * string * string * string * Microsoft.Azure.Management.AppService.Fluent.Models.ApplicationLogsConfig * Microsoft.Azure.Management.AppService.Fluent.Models.HttpLogsConfig * Microsoft.Azure.Management.AppService.Fluent.Models.EnabledConfig * Microsoft.Azure.Management.AppService.Fluent.Models.EnabledConfig -&gt; Microsoft.Azure.Management.AppService.Fluent.Models.SiteLogsConfigInner" Usage="new Microsoft.Azure.Management.AppService.Fluent.Models.SiteLogsConfigInner (id, name, kind, type, applicationLogs, httpLogs, failedRequestsTracing, detailedErrorMessages)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="id" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="kind" Type="System.String" />
        <Parameter Name="type" Type="System.String" />
        <Parameter Name="applicationLogs" Type="Microsoft.Azure.Management.AppService.Fluent.Models.ApplicationLogsConfig" />
        <Parameter Name="httpLogs" Type="Microsoft.Azure.Management.AppService.Fluent.Models.HttpLogsConfig" />
        <Parameter Name="failedRequestsTracing" Type="Microsoft.Azure.Management.AppService.Fluent.Models.EnabledConfig" />
        <Parameter Name="detailedErrorMessages" Type="Microsoft.Azure.Management.AppService.Fluent.Models.EnabledConfig" />
      </Parameters>
      <Docs>
        <param name="id">To be added.</param>
        <param name="name">To be added.</param>
        <param name="kind">To be added.</param>
        <param name="type">To be added.</param>
        <param name="applicationLogs">To be added.</param>
        <param name="httpLogs">To be added.</param>
        <param name="failedRequestsTracing">To be added.</param>
        <param name="detailedErrorMessages">To be added.</param>
        <summary>To be added.</summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ApplicationLogs">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.AppService.Fluent.Models.ApplicationLogsConfig ApplicationLogs { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.AppService.Fluent.Models.ApplicationLogsConfig ApplicationLogs" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.AppService.Fluent.Models.SiteLogsConfigInner.ApplicationLogs" />
      <MemberSignature Language="VB.NET" Value="Public Property ApplicationLogs As ApplicationLogsConfig" />
      <MemberSignature Language="F#" Value="member this.ApplicationLogs : Microsoft.Azure.Management.AppService.Fluent.Models.ApplicationLogsConfig with get, set" Usage="Microsoft.Azure.Management.AppService.Fluent.Models.SiteLogsConfigInner.ApplicationLogs" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.applicationLogs")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.AppService.Fluent.Models.ApplicationLogsConfig</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="5bf47-103">Ruft ab, oder legt ihn fest-Protokolle Anwendungskonfiguration.</span><span class="sxs-lookup"><span data-stu-id="5bf47-103">Gets or sets application logs configuration.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DetailedErrorMessages">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.AppService.Fluent.Models.EnabledConfig DetailedErrorMessages { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.AppService.Fluent.Models.EnabledConfig DetailedErrorMessages" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.AppService.Fluent.Models.SiteLogsConfigInner.DetailedErrorMessages" />
      <MemberSignature Language="VB.NET" Value="Public Property DetailedErrorMessages As EnabledConfig" />
      <MemberSignature Language="F#" Value="member this.DetailedErrorMessages : Microsoft.Azure.Management.AppService.Fluent.Models.EnabledConfig with get, set" Usage="Microsoft.Azure.Management.AppService.Fluent.Models.SiteLogsConfigInner.DetailedErrorMessages" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.detailedErrorMessages")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.AppService.Fluent.Models.EnabledConfig</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="5bf47-104">Ruft ab, oder legt ihn fest ausführliche Meldungen Fehlerkonfiguration.</span><span class="sxs-lookup"><span data-stu-id="5bf47-104">Gets or sets detailed error messages configuration.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="FailedRequestsTracing">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.AppService.Fluent.Models.EnabledConfig FailedRequestsTracing { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.AppService.Fluent.Models.EnabledConfig FailedRequestsTracing" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.AppService.Fluent.Models.SiteLogsConfigInner.FailedRequestsTracing" />
      <MemberSignature Language="VB.NET" Value="Public Property FailedRequestsTracing As EnabledConfig" />
      <MemberSignature Language="F#" Value="member this.FailedRequestsTracing : Microsoft.Azure.Management.AppService.Fluent.Models.EnabledConfig with get, set" Usage="Microsoft.Azure.Management.AppService.Fluent.Models.SiteLogsConfigInner.FailedRequestsTracing" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.failedRequestsTracing")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.AppService.Fluent.Models.EnabledConfig</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="5bf47-105">Ruft ab, oder legt ihn fest Anforderungsfehler Ablaufverfolgungskonfiguration.</span><span class="sxs-lookup"><span data-stu-id="5bf47-105">Gets or sets failed requests tracing configuration.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="HttpLogs">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.AppService.Fluent.Models.HttpLogsConfig HttpLogs { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.AppService.Fluent.Models.HttpLogsConfig HttpLogs" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.AppService.Fluent.Models.SiteLogsConfigInner.HttpLogs" />
      <MemberSignature Language="VB.NET" Value="Public Property HttpLogs As HttpLogsConfig" />
      <MemberSignature Language="F#" Value="member this.HttpLogs : Microsoft.Azure.Management.AppService.Fluent.Models.HttpLogsConfig with get, set" Usage="Microsoft.Azure.Management.AppService.Fluent.Models.SiteLogsConfigInner.HttpLogs" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.httpLogs")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.AppService.Fluent.Models.HttpLogsConfig</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="5bf47-106">Ruft ab, oder legt ihn fest-HTTP-Protokolle Konfiguration.</span><span class="sxs-lookup"><span data-stu-id="5bf47-106">Gets or sets HTTP logs configuration.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Validate">
      <MemberSignature Language="C#" Value="public virtual void Validate ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Validate() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.AppService.Fluent.Models.SiteLogsConfigInner.Validate" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Sub Validate ()" />
      <MemberSignature Language="F#" Value="abstract member Validate : unit -&gt; unit&#xA;override this.Validate : unit -&gt; unit" Usage="siteLogsConfigInner.Validate " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="5bf47-107">Überprüfen Sie das Objekt.</span><span class="sxs-lookup"><span data-stu-id="5bf47-107">Validate the object.</span></span>
            </summary>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="5bf47-108">Wird ausgelöst, wenn die Validierung fehlschlägt</span><span class="sxs-lookup"><span data-stu-id="5bf47-108">Thrown if validation fails</span></span>
            </exception>
      </Docs>
    </Member>
  </Members>
</Type>