<Type Name="IPAddressOrRange" FullName="Microsoft.WindowsAzure.Storage.IPAddressOrRange">
  <TypeSignature Language="C#" Value="public class IPAddressOrRange" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit IPAddressOrRange extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.WindowsAzure.Storage.IPAddressOrRange" />
  <TypeSignature Language="VB.NET" Value="Public Class IPAddressOrRange" />
  <TypeSignature Language="F#" Value="type IPAddressOrRange = class" />
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
            Gibt eine einzelne IP-Adresse oder eine einzelne IP-Adressbereichs (mindestens und einen Höchstwert inklusive).
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public IPAddressOrRange (string address);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string address) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.IPAddressOrRange.#ctor(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (address As String)" />
      <MemberSignature Language="F#" Value="new Microsoft.WindowsAzure.Storage.IPAddressOrRange : string -&gt; Microsoft.WindowsAzure.Storage.IPAddressOrRange" Usage="new Microsoft.WindowsAzure.Storage.IPAddressOrRange address" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="address" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="address">Die IP-Adresse, die dem IPAddressOrRange-Objekt dargestellt werden.</param>
        <summary>
            Initialisiert eine neue Instanz der Klasse IPAddressOrRange über eine einzelne IP-Adresse an.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public IPAddressOrRange (string minimum, string maximum);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string minimum, string maximum) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.IPAddressOrRange.#ctor(System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (minimum As String, maximum As String)" />
      <MemberSignature Language="F#" Value="new Microsoft.WindowsAzure.Storage.IPAddressOrRange : string * string -&gt; Microsoft.WindowsAzure.Storage.IPAddressOrRange" Usage="new Microsoft.WindowsAzure.Storage.IPAddressOrRange (minimum, maximum)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="minimum" Type="System.String" />
        <Parameter Name="maximum" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="minimum">Die minimale IP-Adresse, die das Objekt IPAddressOrRange als Bereichsgrenze, inklusive verwenden.</param>
        <param name="maximum">Die maximale IP-Adresse, die das Objekt IPAddressOrRange als Bereichsgrenze, inklusive verwenden.</param>
        <summary>
            Initialisiert eine neue Instanz der Klasse IPAddressOrRange aus zwei IP-Adresse-Objekte, die eine mindestens einem und höchstens an.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Address">
      <MemberSignature Language="C#" Value="public string Address { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Address" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Storage.IPAddressOrRange.Address" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Address As String" />
      <MemberSignature Language="F#" Value="member this.Address : string" Usage="Microsoft.WindowsAzure.Storage.IPAddressOrRange.Address" />
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
            Die IP-Adresse.
            Gibt null zurück, wenn dieses Objekt einen Bereich von IP-Adressen darstellt.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="IsSingleAddress">
      <MemberSignature Language="C#" Value="public bool IsSingleAddress { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance bool IsSingleAddress" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Storage.IPAddressOrRange.IsSingleAddress" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property IsSingleAddress As Boolean" />
      <MemberSignature Language="F#" Value="member this.IsSingleAddress : bool" Usage="Microsoft.WindowsAzure.Storage.IPAddressOrRange.IsSingleAddress" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            "True", wenn dieses Objekt eine einzelne IP-Adresse "false" stellt, wenn es sich um einen Bereich darstellt.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="MaximumAddress">
      <MemberSignature Language="C#" Value="public string MaximumAddress { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string MaximumAddress" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Storage.IPAddressOrRange.MaximumAddress" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property MaximumAddress As String" />
      <MemberSignature Language="F#" Value="member this.MaximumAddress : string" Usage="Microsoft.WindowsAzure.Storage.IPAddressOrRange.MaximumAddress" />
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
            Die maximale IP-Adresse für den Bereich, inklusiv.
            Gibt null, wenn dieses Objekt stellt eine einzelne IP-Adresse dar.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="MinimumAddress">
      <MemberSignature Language="C#" Value="public string MinimumAddress { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string MinimumAddress" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Storage.IPAddressOrRange.MinimumAddress" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property MinimumAddress As String" />
      <MemberSignature Language="F#" Value="member this.MinimumAddress : string" Usage="Microsoft.WindowsAzure.Storage.IPAddressOrRange.MinimumAddress" />
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
            Die minimale IP-Adresse für den Bereich, inklusiv.
            Gibt null, wenn dieses Objekt stellt eine einzelne IP-Adresse dar.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ToString">
      <MemberSignature Language="C#" Value="public override string ToString ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance string ToString() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.IPAddressOrRange.ToString" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Function ToString () As String" />
      <MemberSignature Language="F#" Value="override this.ToString : unit -&gt; string" Usage="iPAddressOrRange.ToString " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            Stellt eine Zeichenfolgendarstellung dieses Objekts IPAddressOrRange bereit.
            </summary>
        <returns>Die Zeichenfolgendarstellung dieses Objekts IPAddressOrRange.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>