<Type Name="SharedAccessTablePolicy" FullName="Microsoft.WindowsAzure.Storage.Table.SharedAccessTablePolicy">
  <TypeSignature Language="C#" Value="public sealed class SharedAccessTablePolicy" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed beforefieldinit SharedAccessTablePolicy extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.WindowsAzure.Storage.Table.SharedAccessTablePolicy" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class SharedAccessTablePolicy" />
  <TypeSignature Language="F#" Value="type SharedAccessTablePolicy = class" />
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
            Stellt eine SAS-Richtlinie, die die Startzeit, Ablaufzeit und Berechtigungen für eine SAS angibt.
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public SharedAccessTablePolicy ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Table.SharedAccessTablePolicy.#ctor" />
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
            Initialisiert eine neue Instanz der SharedAccessTablePolicy-Klasse.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Permissions">
      <MemberSignature Language="C#" Value="public Microsoft.WindowsAzure.Storage.Table.SharedAccessTablePermissions Permissions { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype Microsoft.WindowsAzure.Storage.Table.SharedAccessTablePermissions Permissions" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Storage.Table.SharedAccessTablePolicy.Permissions" />
      <MemberSignature Language="VB.NET" Value="Public Property Permissions As SharedAccessTablePermissions" />
      <MemberSignature Language="F#" Value="member this.Permissions : Microsoft.WindowsAzure.Storage.Table.SharedAccessTablePermissions with get, set" Usage="Microsoft.WindowsAzure.Storage.Table.SharedAccessTablePolicy.Permissions" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.WindowsAzure.Storage.Table.SharedAccessTablePermissions</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt die Berechtigungen für eine shared Access Signature, die mit dieser SAS-Richtlinie verknüpft ist.
            </summary>
        <value>Ein <see cref="T:Microsoft.WindowsAzure.Storage.Table.SharedAccessTablePermissions" />-Objekt.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="PermissionsFromString">
      <MemberSignature Language="C#" Value="public static Microsoft.WindowsAzure.Storage.Table.SharedAccessTablePermissions PermissionsFromString (string input);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig valuetype Microsoft.WindowsAzure.Storage.Table.SharedAccessTablePermissions PermissionsFromString(string input) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Table.SharedAccessTablePolicy.PermissionsFromString(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function PermissionsFromString (input As String) As SharedAccessTablePermissions" />
      <MemberSignature Language="F#" Value="static member PermissionsFromString : string -&gt; Microsoft.WindowsAzure.Storage.Table.SharedAccessTablePermissions" Usage="Microsoft.WindowsAzure.Storage.Table.SharedAccessTablePolicy.PermissionsFromString input" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.WindowsAzure.Storage.Table.SharedAccessTablePermissions</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="input" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="input">Die SAS-Berechtigungen im Zeichenfolgenformat.</param>
        <summary>
            Erstellt eine <see cref="T:Microsoft.WindowsAzure.Storage.Table.SharedAccessTablePermissions" /> Objekt aus einer Berechtigungszeichenfolge.
            </summary>
        <returns>Ein <see cref="T:Microsoft.WindowsAzure.Storage.Table.SharedAccessTablePermissions" />-Objekt.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="PermissionsToString">
      <MemberSignature Language="C#" Value="public static string PermissionsToString (Microsoft.WindowsAzure.Storage.Table.SharedAccessTablePermissions permissions);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig string PermissionsToString(valuetype Microsoft.WindowsAzure.Storage.Table.SharedAccessTablePermissions permissions) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Table.SharedAccessTablePolicy.PermissionsToString(Microsoft.WindowsAzure.Storage.Table.SharedAccessTablePermissions)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function PermissionsToString (permissions As SharedAccessTablePermissions) As String" />
      <MemberSignature Language="F#" Value="static member PermissionsToString : Microsoft.WindowsAzure.Storage.Table.SharedAccessTablePermissions -&gt; string" Usage="Microsoft.WindowsAzure.Storage.Table.SharedAccessTablePolicy.PermissionsToString permissions" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="permissions" Type="Microsoft.WindowsAzure.Storage.Table.SharedAccessTablePermissions" />
      </Parameters>
      <Docs>
        <param name="permissions">Ein <see cref="T:Microsoft.WindowsAzure.Storage.Table.SharedAccessTablePermissions" />-Objekt.</param>
        <summary>
            Konvertiert die Berechtigungen für die SAS-Richtlinie in eine Zeichenfolge angegeben.
            </summary>
        <returns>Die SAS-Berechtigungen im Zeichenfolgenformat.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SharedAccessExpiryTime">
      <MemberSignature Language="C#" Value="public Nullable&lt;DateTimeOffset&gt; SharedAccessExpiryTime { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype System.DateTimeOffset&gt; SharedAccessExpiryTime" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Storage.Table.SharedAccessTablePolicy.SharedAccessExpiryTime" />
      <MemberSignature Language="VB.NET" Value="Public Property SharedAccessExpiryTime As Nullable(Of DateTimeOffset)" />
      <MemberSignature Language="F#" Value="member this.SharedAccessExpiryTime : Nullable&lt;DateTimeOffset&gt; with get, set" Usage="Microsoft.WindowsAzure.Storage.Table.SharedAccessTablePolicy.SharedAccessExpiryTime" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.DateTimeOffset&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt die Ablaufzeit für eine shared Access Signature, die mit dieser SAS-Richtlinie verknüpft ist.
            </summary>
        <value>Ein <see cref="T:System.DateTimeOffset" /> die Ablaufzeit der SAS angeben.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SharedAccessStartTime">
      <MemberSignature Language="C#" Value="public Nullable&lt;DateTimeOffset&gt; SharedAccessStartTime { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype System.DateTimeOffset&gt; SharedAccessStartTime" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Storage.Table.SharedAccessTablePolicy.SharedAccessStartTime" />
      <MemberSignature Language="VB.NET" Value="Public Property SharedAccessStartTime As Nullable(Of DateTimeOffset)" />
      <MemberSignature Language="F#" Value="member this.SharedAccessStartTime : Nullable&lt;DateTimeOffset&gt; with get, set" Usage="Microsoft.WindowsAzure.Storage.Table.SharedAccessTablePolicy.SharedAccessStartTime" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.DateTimeOffset&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt die Startzeit für eine shared Access Signature, die mit dieser SAS-Richtlinie verknüpft ist.
            </summary>
        <value>Ein <see cref="T:System.DateTimeOffset" /> Startzeit für den gemeinsamen Zugriff angibt.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>