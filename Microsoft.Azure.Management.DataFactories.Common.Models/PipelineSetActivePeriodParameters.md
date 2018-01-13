<Type Name="PipelineSetActivePeriodParameters" FullName="Microsoft.Azure.Management.DataFactories.Common.Models.PipelineSetActivePeriodParameters">
  <TypeSignature Language="C#" Value="public class PipelineSetActivePeriodParameters" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit PipelineSetActivePeriodParameters extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.DataFactories.Common.Models.PipelineSetActivePeriodParameters" />
  <TypeSignature Language="VB.NET" Value="Public Class PipelineSetActivePeriodParameters" />
  <TypeSignature Language="F#" Value="type PipelineSetActivePeriodParameters = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
    <AssemblyVersion>4.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            Parameter, die den aktiven Zeitraum für die Pipeline aktiven Zeitraum Operation angibt.
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public PipelineSetActivePeriodParameters ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactories.Common.Models.PipelineSetActivePeriodParameters.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            Initialisiert eine neue Instanz der PipelineSetActivePeriodParameters-Klasse.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public PipelineSetActivePeriodParameters (string activePeriodStartTime, string activePeriodEndTime);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string activePeriodStartTime, string activePeriodEndTime) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactories.Common.Models.PipelineSetActivePeriodParameters.#ctor(System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (activePeriodStartTime As String, activePeriodEndTime As String)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.DataFactories.Common.Models.PipelineSetActivePeriodParameters : string * string -&gt; Microsoft.Azure.Management.DataFactories.Common.Models.PipelineSetActivePeriodParameters" Usage="new Microsoft.Azure.Management.DataFactories.Common.Models.PipelineSetActivePeriodParameters (activePeriodStartTime, activePeriodEndTime)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="activePeriodStartTime" Type="System.String" />
        <Parameter Name="activePeriodEndTime" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="activePeriodStartTime">To be added.</param>
        <param name="activePeriodEndTime">To be added.</param>
        <summary>
            Initialisiert eine neue Instanz der PipelineSetActivePeriodParameters-Klasse mit erforderlichen Argumenten.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ActivePeriodEndTime">
      <MemberSignature Language="C#" Value="public string ActivePeriodEndTime { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ActivePeriodEndTime" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactories.Common.Models.PipelineSetActivePeriodParameters.ActivePeriodEndTime" />
      <MemberSignature Language="VB.NET" Value="Public Property ActivePeriodEndTime As String" />
      <MemberSignature Language="F#" Value="member this.ActivePeriodEndTime : string with get, set" Usage="Microsoft.Azure.Management.DataFactories.Common.Models.PipelineSetActivePeriodParameters.ActivePeriodEndTime" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Erforderlich. Pipeline-Endzeit im Round-Trip ISO 8601-Format.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ActivePeriodStartTime">
      <MemberSignature Language="C#" Value="public string ActivePeriodStartTime { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ActivePeriodStartTime" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactories.Common.Models.PipelineSetActivePeriodParameters.ActivePeriodStartTime" />
      <MemberSignature Language="VB.NET" Value="Public Property ActivePeriodStartTime As String" />
      <MemberSignature Language="F#" Value="member this.ActivePeriodStartTime : string with get, set" Usage="Microsoft.Azure.Management.DataFactories.Common.Models.PipelineSetActivePeriodParameters.ActivePeriodStartTime" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Erforderlich. Die Startzeit für eine Pipeline im Round-Trip ISO 8601-Format.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AutoResolve">
      <MemberSignature Language="C#" Value="public bool AutoResolve { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance bool AutoResolve" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactories.Common.Models.PipelineSetActivePeriodParameters.AutoResolve" />
      <MemberSignature Language="VB.NET" Value="Public Property AutoResolve As Boolean" />
      <MemberSignature Language="F#" Value="member this.AutoResolve : bool with get, set" Usage="Microsoft.Azure.Management.DataFactories.Common.Models.PipelineSetActivePeriodParameters.AutoResolve" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Optional. Automatisch beheben, aktiven Zeiträume von in Konflikt stehenden Pipelines.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ForceRecalc">
      <MemberSignature Language="C#" Value="public bool ForceRecalc { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance bool ForceRecalc" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactories.Common.Models.PipelineSetActivePeriodParameters.ForceRecalc" />
      <MemberSignature Language="VB.NET" Value="Public Property ForceRecalc As Boolean" />
      <MemberSignature Language="F#" Value="member this.ForceRecalc : bool with get, set" Usage="Microsoft.Azure.Management.DataFactories.Common.Models.PipelineSetActivePeriodParameters.ForceRecalc" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Optional. Markieren Sie alle Segmente im Zeitraum als ausstehende Ausführung.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>