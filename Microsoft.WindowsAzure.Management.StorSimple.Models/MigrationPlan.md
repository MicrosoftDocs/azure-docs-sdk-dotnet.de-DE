<Type Name="MigrationPlan" FullName="Microsoft.WindowsAzure.Management.StorSimple.Models.MigrationPlan">
  <TypeSignature Language="C#" Value="public class MigrationPlan" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit MigrationPlan extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.WindowsAzure.Management.StorSimple.Models.MigrationPlan" />
  <TypeSignature Language="VB.NET" Value="Public Class MigrationPlan" />
  <TypeSignature Language="F#" Value="type MigrationPlan = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.WindowsAzure.Management.StorSimple</AssemblyName>
    <AssemblyVersion>1.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            Migration Plan-Klasse
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public MigrationPlan ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Management.StorSimple.Models.MigrationPlan.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Management.StorSimple</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            Initialisiert eine neue Instanz der MigrationPlan-Klasse.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public MigrationPlan (string configId, string deviceName, System.Collections.Generic.List&lt;Microsoft.WindowsAzure.Management.StorSimple.Models.MigrationPlanInfo&gt; migrationPlanInfo);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string configId, string deviceName, class System.Collections.Generic.List`1&lt;class Microsoft.WindowsAzure.Management.StorSimple.Models.MigrationPlanInfo&gt; migrationPlanInfo) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Management.StorSimple.Models.MigrationPlan.#ctor(System.String,System.String,System.Collections.Generic.List{Microsoft.WindowsAzure.Management.StorSimple.Models.MigrationPlanInfo})" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (configId As String, deviceName As String, migrationPlanInfo As List(Of MigrationPlanInfo))" />
      <MemberSignature Language="F#" Value="new Microsoft.WindowsAzure.Management.StorSimple.Models.MigrationPlan : string * string * System.Collections.Generic.List&lt;Microsoft.WindowsAzure.Management.StorSimple.Models.MigrationPlanInfo&gt; -&gt; Microsoft.WindowsAzure.Management.StorSimple.Models.MigrationPlan" Usage="new Microsoft.WindowsAzure.Management.StorSimple.Models.MigrationPlan (configId, deviceName, migrationPlanInfo)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Management.StorSimple</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="configId" Type="System.String" />
        <Parameter Name="deviceName" Type="System.String" />
        <Parameter Name="migrationPlanInfo" Type="System.Collections.Generic.List&lt;Microsoft.WindowsAzure.Management.StorSimple.Models.MigrationPlanInfo&gt;" />
      </Parameters>
      <Docs>
        <param name="configId">To be added.</param>
        <param name="deviceName">To be added.</param>
        <param name="migrationPlanInfo">To be added.</param>
        <summary>
            Initialisiert eine neue Instanz der MigrationPlan-Klasse mit erforderlichen Argumenten.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ConfigId">
      <MemberSignature Language="C#" Value="public string ConfigId { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ConfigId" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Management.StorSimple.Models.MigrationPlan.ConfigId" />
      <MemberSignature Language="VB.NET" Value="Public Property ConfigId As String" />
      <MemberSignature Language="F#" Value="member this.ConfigId : string with get, set" Usage="Microsoft.WindowsAzure.Management.StorSimple.Models.MigrationPlan.ConfigId" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Management.StorSimple</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Erforderlich. Ruft ab oder legt ihn fest übergebene beim Importieren der config-Datei der Konfigurations-ID
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeviceName">
      <MemberSignature Language="C#" Value="public string DeviceName { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string DeviceName" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Management.StorSimple.Models.MigrationPlan.DeviceName" />
      <MemberSignature Language="VB.NET" Value="Public Property DeviceName As String" />
      <MemberSignature Language="F#" Value="member this.DeviceName : string with get, set" Usage="Microsoft.WindowsAzure.Management.StorSimple.Models.MigrationPlan.DeviceName" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Management.StorSimple</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Erforderlich. Ruft ab oder legt die Ziel-Gerätename, in dem der Migrationsplan berechnet wird
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="MigrationPlanInfo">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;Microsoft.WindowsAzure.Management.StorSimple.Models.MigrationPlanInfo&gt; MigrationPlanInfo { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class Microsoft.WindowsAzure.Management.StorSimple.Models.MigrationPlanInfo&gt; MigrationPlanInfo" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Management.StorSimple.Models.MigrationPlan.MigrationPlanInfo" />
      <MemberSignature Language="VB.NET" Value="Public Property MigrationPlanInfo As IList(Of MigrationPlanInfo)" />
      <MemberSignature Language="F#" Value="member this.MigrationPlanInfo : System.Collections.Generic.IList&lt;Microsoft.WindowsAzure.Management.StorSimple.Models.MigrationPlanInfo&gt; with get, set" Usage="Microsoft.WindowsAzure.Management.StorSimple.Models.MigrationPlan.MigrationPlanInfo" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Management.StorSimple</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;Microsoft.WindowsAzure.Management.StorSimple.Models.MigrationPlanInfo&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Erforderlich. Ruft ab oder legt Liste der Migrationspläne für alle in der importierten Config angegebenen Datencontainer
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>