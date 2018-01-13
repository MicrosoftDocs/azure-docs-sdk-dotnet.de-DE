<Type Name="ClaimsCredentials" FullName="System.Fabric.ClaimsCredentials">
  <TypeSignature Language="C#" Value="public sealed class ClaimsCredentials : System.Fabric.SecurityCredentials" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed beforefieldinit ClaimsCredentials extends System.Fabric.SecurityCredentials" />
  <TypeSignature Language="DocId" Value="T:System.Fabric.ClaimsCredentials" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class ClaimsCredentials&#xA;Inherits SecurityCredentials" />
  <TypeSignature Language="F#" Value="type ClaimsCredentials = class&#xA;    inherit SecurityCredentials" />
  <AssemblyInfo>
    <AssemblyName>System.Fabric</AssemblyName>
    <AssemblyVersion>6.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Fabric.SecurityCredentials</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
      <para>Stellt-Anspruchs basierend Sicherheitsanmeldeinformationen aus STS (Sicherheitstokendienst) abgerufen.</para>
    </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ClaimsCredentials ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.ClaimsCredentials.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
          <para>Initialisiert eine neue Instanz der <see cref="T:System.Fabric.ClaimsCredentials" />-Klasse.</para>
        </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="IssuerThumbprints">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;string&gt; IssuerThumbprints { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;string&gt; IssuerThumbprints" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.ClaimsCredentials.IssuerThumbprints" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property IssuerThumbprints As IList(Of String)" />
      <MemberSignature Language="F#" Value="member this.IssuerThumbprints : System.Collections.Generic.IList&lt;string&gt;" Usage="System.Fabric.ClaimsCredentials.IssuerThumbprints" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;System.String&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para>Ruft die zertifikatfingerabdrücke der Server Aussteller des Zertifikats ab.</para>
        </summary>
        <value>
          <para>Die zertifikatfingerabdrücke der Server Aussteller des Zertifikats.</para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="LocalClaims">
      <MemberSignature Language="C#" Value="public string LocalClaims { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string LocalClaims" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.ClaimsCredentials.LocalClaims" />
      <MemberSignature Language="VB.NET" Value="Public Property LocalClaims As String" />
      <MemberSignature Language="F#" Value="member this.LocalClaims : string with get, set" Usage="System.Fabric.ClaimsCredentials.LocalClaims" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para>Ruft eine Zeichenfolgendarstellung von Claims-Token vom STS (Sicherheitstokendienst) bezogen.</para>
        </summary>
        <value>
          <para>Die Zeichenfolgendarstellung des Claims-Token vom STS (Sicherheitstokendienst) bezogen werden soll.</para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ProtectionLevel">
      <MemberSignature Language="C#" Value="public System.Fabric.ProtectionLevel ProtectionLevel { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Fabric.ProtectionLevel ProtectionLevel" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.ClaimsCredentials.ProtectionLevel" />
      <MemberSignature Language="VB.NET" Value="Public Property ProtectionLevel As ProtectionLevel" />
      <MemberSignature Language="F#" Value="member this.ProtectionLevel : System.Fabric.ProtectionLevel with get, set" Usage="System.Fabric.ClaimsCredentials.ProtectionLevel" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.ProtectionLevel</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para>Ruft die Schutzebene der Kommunikation mit dem Server ab. Der Standardwert ist <see cref="F:System.Fabric.ProtectionLevel.EncryptAndSign" />.</para>
        </summary>
        <value>
          <para>Die Schutzebene der Kommunikation mit dem Server.</para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ServerCommonNames">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;string&gt; ServerCommonNames { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;string&gt; ServerCommonNames" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.ClaimsCredentials.ServerCommonNames" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ServerCommonNames As IList(Of String)" />
      <MemberSignature Language="F#" Value="member this.ServerCommonNames : System.Collections.Generic.IList&lt;string&gt;" Usage="System.Fabric.ClaimsCredentials.ServerCommonNames" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;System.String&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para>Ruft die erwartete allgemeinen Namen des Zertifikats ab.</para>
        </summary>
        <value>
          <para>Die erwartete allgemeinen Namen des Server-Zertifikats.</para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ServerThumbprints">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;string&gt; ServerThumbprints { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;string&gt; ServerThumbprints" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.ClaimsCredentials.ServerThumbprints" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ServerThumbprints As IList(Of String)" />
      <MemberSignature Language="F#" Value="member this.ServerThumbprints : System.Collections.Generic.IList&lt;string&gt;" Usage="System.Fabric.ClaimsCredentials.ServerThumbprints" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;System.String&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            NUR ZUR INTERNEN VERWENDUNG.
            </summary>
        <value>NUR ZUR INTERNEN VERWENDUNG.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>