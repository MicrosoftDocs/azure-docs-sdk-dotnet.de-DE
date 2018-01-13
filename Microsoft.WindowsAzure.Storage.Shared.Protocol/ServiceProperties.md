<Type Name="ServiceProperties" FullName="Microsoft.WindowsAzure.Storage.Shared.Protocol.ServiceProperties">
  <TypeSignature Language="C#" Value="public sealed class ServiceProperties" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed beforefieldinit ServiceProperties extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.WindowsAzure.Storage.Shared.Protocol.ServiceProperties" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class ServiceProperties" />
  <TypeSignature Language="F#" Value="type ServiceProperties = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
    <AssemblyVersion>8.4.0.0</AssemblyVersion>
    <AssemblyVersion>8.7.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            Klasse, die einen Satz von Eigenschaften für einen Cloud-Speicherdienst darstellt.
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ServiceProperties ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Shared.Protocol.ServiceProperties.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            Initialisiert eine neue Instanz der ServiceProperties-Klasse.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ServiceProperties (Microsoft.WindowsAzure.Storage.Shared.Protocol.LoggingProperties logging = null, Microsoft.WindowsAzure.Storage.Shared.Protocol.MetricsProperties hourMetrics = null, Microsoft.WindowsAzure.Storage.Shared.Protocol.MetricsProperties minuteMetrics = null, Microsoft.WindowsAzure.Storage.Shared.Protocol.CorsProperties cors = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class Microsoft.WindowsAzure.Storage.Shared.Protocol.LoggingProperties logging, class Microsoft.WindowsAzure.Storage.Shared.Protocol.MetricsProperties hourMetrics, class Microsoft.WindowsAzure.Storage.Shared.Protocol.MetricsProperties minuteMetrics, class Microsoft.WindowsAzure.Storage.Shared.Protocol.CorsProperties cors) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Shared.Protocol.ServiceProperties.#ctor(Microsoft.WindowsAzure.Storage.Shared.Protocol.LoggingProperties,Microsoft.WindowsAzure.Storage.Shared.Protocol.MetricsProperties,Microsoft.WindowsAzure.Storage.Shared.Protocol.MetricsProperties,Microsoft.WindowsAzure.Storage.Shared.Protocol.CorsProperties)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional logging As LoggingProperties = null, Optional hourMetrics As MetricsProperties = null, Optional minuteMetrics As MetricsProperties = null, Optional cors As CorsProperties = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.WindowsAzure.Storage.Shared.Protocol.ServiceProperties : Microsoft.WindowsAzure.Storage.Shared.Protocol.LoggingProperties * Microsoft.WindowsAzure.Storage.Shared.Protocol.MetricsProperties * Microsoft.WindowsAzure.Storage.Shared.Protocol.MetricsProperties * Microsoft.WindowsAzure.Storage.Shared.Protocol.CorsProperties -&gt; Microsoft.WindowsAzure.Storage.Shared.Protocol.ServiceProperties" Usage="new Microsoft.WindowsAzure.Storage.Shared.Protocol.ServiceProperties (logging, hourMetrics, minuteMetrics, cors)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="logging" Type="Microsoft.WindowsAzure.Storage.Shared.Protocol.LoggingProperties" />
        <Parameter Name="hourMetrics" Type="Microsoft.WindowsAzure.Storage.Shared.Protocol.MetricsProperties" />
        <Parameter Name="minuteMetrics" Type="Microsoft.WindowsAzure.Storage.Shared.Protocol.MetricsProperties" />
        <Parameter Name="cors" Type="Microsoft.WindowsAzure.Storage.Shared.Protocol.CorsProperties" />
      </Parameters>
      <Docs>
        <param name="logging">To be added.</param>
        <param name="hourMetrics">To be added.</param>
        <param name="minuteMetrics">To be added.</param>
        <param name="cors">To be added.</param>
        <summary>
            Initialisiert eine neue Instanz der ServiceProperties-Klasse.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Cors">
      <MemberSignature Language="C#" Value="public Microsoft.WindowsAzure.Storage.Shared.Protocol.CorsProperties Cors { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.WindowsAzure.Storage.Shared.Protocol.CorsProperties Cors" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Storage.Shared.Protocol.ServiceProperties.Cors" />
      <MemberSignature Language="VB.NET" Value="Public Property Cors As CorsProperties" />
      <MemberSignature Language="F#" Value="member this.Cors : Microsoft.WindowsAzure.Storage.Shared.Protocol.CorsProperties with get, set" Usage="Microsoft.WindowsAzure.Storage.Shared.Protocol.ServiceProperties.Cors" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.WindowsAzure.Storage.Shared.Protocol.CorsProperties</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt die Eigenschaften des Cross Origin Resource Sharing (CORS) fest.
            </summary>
        <value>Die CORS-Eigenschaften.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DefaultServiceVersion">
      <MemberSignature Language="C#" Value="public string DefaultServiceVersion { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string DefaultServiceVersion" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Storage.Shared.Protocol.ServiceProperties.DefaultServiceVersion" />
      <MemberSignature Language="VB.NET" Value="Public Property DefaultServiceVersion As String" />
      <MemberSignature Language="F#" Value="member this.DefaultServiceVersion : string with get, set" Usage="Microsoft.WindowsAzure.Storage.Shared.Protocol.ServiceProperties.DefaultServiceVersion" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt die standarddienstversion.
            </summary>
        <value>Der Standarddienst-Versionsbezeichner.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="HourMetrics">
      <MemberSignature Language="C#" Value="public Microsoft.WindowsAzure.Storage.Shared.Protocol.MetricsProperties HourMetrics { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.WindowsAzure.Storage.Shared.Protocol.MetricsProperties HourMetrics" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Storage.Shared.Protocol.ServiceProperties.HourMetrics" />
      <MemberSignature Language="VB.NET" Value="Public Property HourMetrics As MetricsProperties" />
      <MemberSignature Language="F#" Value="member this.HourMetrics : Microsoft.WindowsAzure.Storage.Shared.Protocol.MetricsProperties with get, set" Usage="Microsoft.WindowsAzure.Storage.Shared.Protocol.ServiceProperties.HourMetrics" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.WindowsAzure.Storage.Shared.Protocol.MetricsProperties</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt sie fest Stunde Metriken.
            </summary>
        <value>Die metrikeigenschaften.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Logging">
      <MemberSignature Language="C#" Value="public Microsoft.WindowsAzure.Storage.Shared.Protocol.LoggingProperties Logging { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.WindowsAzure.Storage.Shared.Protocol.LoggingProperties Logging" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Storage.Shared.Protocol.ServiceProperties.Logging" />
      <MemberSignature Language="VB.NET" Value="Public Property Logging As LoggingProperties" />
      <MemberSignature Language="F#" Value="member this.Logging : Microsoft.WindowsAzure.Storage.Shared.Protocol.LoggingProperties with get, set" Usage="Microsoft.WindowsAzure.Storage.Shared.Protocol.ServiceProperties.Logging" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.WindowsAzure.Storage.Shared.Protocol.LoggingProperties</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt die Protokollierungseigenschaften.
            </summary>
        <value>Die Protokollierungseigenschaften.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="MinuteMetrics">
      <MemberSignature Language="C#" Value="public Microsoft.WindowsAzure.Storage.Shared.Protocol.MetricsProperties MinuteMetrics { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.WindowsAzure.Storage.Shared.Protocol.MetricsProperties MinuteMetrics" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Storage.Shared.Protocol.ServiceProperties.MinuteMetrics" />
      <MemberSignature Language="VB.NET" Value="Public Property MinuteMetrics As MetricsProperties" />
      <MemberSignature Language="F#" Value="member this.MinuteMetrics : Microsoft.WindowsAzure.Storage.Shared.Protocol.MetricsProperties with get, set" Usage="Microsoft.WindowsAzure.Storage.Shared.Protocol.ServiceProperties.MinuteMetrics" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.WindowsAzure.Storage.Shared.Protocol.MetricsProperties</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt die minutenmetrikeigenschaften.
            </summary>
        <value>Die minutenmetrikeigenschaften.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>