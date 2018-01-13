<Type Name="StorageUri" FullName="Microsoft.WindowsAzure.Storage.StorageUri">
  <TypeSignature Language="C#" Value="public sealed class StorageUri : IEquatable&lt;Microsoft.WindowsAzure.Storage.StorageUri&gt;" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed beforefieldinit StorageUri extends System.Object implements class System.IEquatable`1&lt;class Microsoft.WindowsAzure.Storage.StorageUri&gt;" />
  <TypeSignature Language="DocId" Value="T:Microsoft.WindowsAzure.Storage.StorageUri" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class StorageUri&#xA;Implements IEquatable(Of StorageUri)" />
  <TypeSignature Language="F#" Value="type StorageUri = class&#xA;    interface IEquatable&lt;StorageUri&gt;" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
    <AssemblyVersion>8.4.0.0</AssemblyVersion>
    <AssemblyVersion>8.7.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces>
    <Interface>
      <InterfaceName>System.IEquatable&lt;Microsoft.WindowsAzure.Storage.StorageUri&gt;</InterfaceName>
    </Interface>
  </Interfaces>
  <Docs>
    <summary>
            Enthält die URIs für die primären und sekundären Speicherorte einer Microsoft Azure Storage-Ressource.
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public StorageUri (Uri primaryUri);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class System.Uri primaryUri) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.StorageUri.#ctor(System.Uri)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (primaryUri As Uri)" />
      <MemberSignature Language="F#" Value="new Microsoft.WindowsAzure.Storage.StorageUri : Uri -&gt; Microsoft.WindowsAzure.Storage.StorageUri" Usage="new Microsoft.WindowsAzure.Storage.StorageUri primaryUri" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="primaryUri" Type="System.Uri" />
      </Parameters>
      <Docs>
        <param name="primaryUri">Die <see cref="T:System.Uri" /> für den primären Endpunkt.</param>
        <summary>
            Initialisiert eine neue Instanz der dem <see cref="T:Microsoft.WindowsAzure.Storage.StorageUri" /> -Klasse mit den primären Endpunkt für das Speicherkonto an.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public StorageUri (Uri primaryUri, Uri secondaryUri);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class System.Uri primaryUri, class System.Uri secondaryUri) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.StorageUri.#ctor(System.Uri,System.Uri)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (primaryUri As Uri, secondaryUri As Uri)" />
      <MemberSignature Language="F#" Value="new Microsoft.WindowsAzure.Storage.StorageUri : Uri * Uri -&gt; Microsoft.WindowsAzure.Storage.StorageUri" Usage="new Microsoft.WindowsAzure.Storage.StorageUri (primaryUri, secondaryUri)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="primaryUri" Type="System.Uri" />
        <Parameter Name="secondaryUri" Type="System.Uri" />
      </Parameters>
      <Docs>
        <param name="primaryUri">Die <see cref="T:System.Uri" /> für den primären Endpunkt.</param>
        <param name="secondaryUri">Die <see cref="T:System.Uri" /> für den sekundären Endpunkt.</param>
        <summary>
            Initialisiert eine neue Instanz der dem <see cref="T:Microsoft.WindowsAzure.Storage.StorageUri" /> -Klasse unter Verwendung der primären und sekundären Endpunkte für das Speicherkonto an.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Equals">
      <MemberSignature Language="C#" Value="public bool Equals (Microsoft.WindowsAzure.Storage.StorageUri other);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance bool Equals(class Microsoft.WindowsAzure.Storage.StorageUri other) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.StorageUri.Equals(Microsoft.WindowsAzure.Storage.StorageUri)" />
      <MemberSignature Language="VB.NET" Value="Public Function Equals (other As StorageUri) As Boolean" />
      <MemberSignature Language="F#" Value="override this.Equals : Microsoft.WindowsAzure.Storage.StorageUri -&gt; bool" Usage="storageUri.Equals other" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:System.IEquatable`1.Equals(`0)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="other" Type="Microsoft.WindowsAzure.Storage.StorageUri" />
      </Parameters>
      <Docs>
        <param name="other">Ein Objekt, das mit diesem Objekt verglichen werden soll.</param>
        <summary>
            Gibt an, ob das aktuelle Objekt gleich einem anderen Objekt des gleichen Typs ist.
            </summary>
        <returns>
          <c>"true"</c> Wenn das aktuelle Objekt gleich dem <paramref name="other" /> Parameter ist, andernfalls <c>"false"</c>.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Equals">
      <MemberSignature Language="C#" Value="public override bool Equals (object obj);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance bool Equals(object obj) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.StorageUri.Equals(System.Object)" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Function Equals (obj As Object) As Boolean" />
      <MemberSignature Language="F#" Value="override this.Equals : obj -&gt; bool" Usage="storageUri.Equals obj" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="obj" Type="System.Object" />
      </Parameters>
      <Docs>
        <param name="obj">Der <see cref="T:System.Object" />, der mit dieser Instanz verglichen werden soll.</param>
        <summary>
            Bestimmt, ob der angegebene <see cref="T:System.Object" /> gleich dieser Instanz ist.
            </summary>
        <returns>
          <c>"true"</c> Wenn das angegebene <see cref="T:System.Object" /> gleich dieser Instanz ist, andernfalls <c>"false"</c>.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetHashCode">
      <MemberSignature Language="C#" Value="public override int GetHashCode ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance int32 GetHashCode() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.StorageUri.GetHashCode" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Function GetHashCode () As Integer" />
      <MemberSignature Language="F#" Value="override this.GetHashCode : unit -&gt; int" Usage="storageUri.GetHashCode " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Int32</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            Gibt einen Hashcode für diese Instanz zurück.
            </summary>
        <returns>
            Ein Hashcode für diese Instanz, der zur Verwendung in Hashalgorithmen und Hashdatenstrukturen, z. B. einer Hashtabelle, geeignet ist. 
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetUri">
      <MemberSignature Language="C#" Value="public Uri GetUri (Microsoft.WindowsAzure.Storage.StorageLocation location);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Uri GetUri(valuetype Microsoft.WindowsAzure.Storage.StorageLocation location) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.StorageUri.GetUri(Microsoft.WindowsAzure.Storage.StorageLocation)" />
      <MemberSignature Language="VB.NET" Value="Public Function GetUri (location As StorageLocation) As Uri" />
      <MemberSignature Language="F#" Value="member this.GetUri : Microsoft.WindowsAzure.Storage.StorageLocation -&gt; Uri" Usage="storageUri.GetUri location" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Uri</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="location" Type="Microsoft.WindowsAzure.Storage.StorageLocation" />
      </Parameters>
      <Docs>
        <param name="location">Ein <see cref="T:Microsoft.WindowsAzure.Storage.StorageLocation" />-Enumerationswert.</param>
        <summary>
            Gibt den URI für den speicherkontoendpunkt am angegebenen Speicherort zurück.
            </summary>
        <returns>Die <see cref="T:System.Uri" /> für den Endpunkt an der angegebenen Position.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="op_Equality">
      <MemberSignature Language="C#" Value="public static bool operator == (Microsoft.WindowsAzure.Storage.StorageUri uri1, Microsoft.WindowsAzure.Storage.StorageUri uri2);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig specialname bool op_Equality(class Microsoft.WindowsAzure.Storage.StorageUri uri1, class Microsoft.WindowsAzure.Storage.StorageUri uri2) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.StorageUri.op_Equality(Microsoft.WindowsAzure.Storage.StorageUri,Microsoft.WindowsAzure.Storage.StorageUri)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Operator == (uri1 As StorageUri, uri2 As StorageUri) As Boolean" />
      <MemberSignature Language="F#" Value="static member ( = ) : Microsoft.WindowsAzure.Storage.StorageUri * Microsoft.WindowsAzure.Storage.StorageUri -&gt; bool" Usage="uri1 = uri2" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="uri1" Type="Microsoft.WindowsAzure.Storage.StorageUri" />
        <Parameter Name="uri2" Type="Microsoft.WindowsAzure.Storage.StorageUri" />
      </Parameters>
      <Docs>
        <param name="uri1">Das erste zu vergleichende <see cref="T:Microsoft.WindowsAzure.Storage.StorageUri" />-Objekt.</param>
        <param name="uri2">Das zweite zu vergleichende <see cref="T:Microsoft.WindowsAzure.Storage.StorageUri" />-Objekt.</param>
        <summary>
            Vergleicht zwei <see cref="T:Microsoft.WindowsAzure.Storage.StorageUri" /> Objekte auf Äquivalenz.
            </summary>
        <returns>
          <c>"true"</c> Wenn die <see cref="T:Microsoft.WindowsAzure.Storage.StorageUri" /> -Objekte gleiche Werte haben; andernfalls <c>"false"</c>.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="op_Inequality">
      <MemberSignature Language="C#" Value="public static bool operator != (Microsoft.WindowsAzure.Storage.StorageUri uri1, Microsoft.WindowsAzure.Storage.StorageUri uri2);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig specialname bool op_Inequality(class Microsoft.WindowsAzure.Storage.StorageUri uri1, class Microsoft.WindowsAzure.Storage.StorageUri uri2) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.StorageUri.op_Inequality(Microsoft.WindowsAzure.Storage.StorageUri,Microsoft.WindowsAzure.Storage.StorageUri)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Operator != (uri1 As StorageUri, uri2 As StorageUri) As Boolean" />
      <MemberSignature Language="F#" Value="static member op_Inequality : Microsoft.WindowsAzure.Storage.StorageUri * Microsoft.WindowsAzure.Storage.StorageUri -&gt; bool" Usage="Microsoft.WindowsAzure.Storage.StorageUri.op_Inequality (uri1, uri2)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="uri1" Type="Microsoft.WindowsAzure.Storage.StorageUri" />
        <Parameter Name="uri2" Type="Microsoft.WindowsAzure.Storage.StorageUri" />
      </Parameters>
      <Docs>
        <param name="uri1">Das erste zu vergleichende <see cref="T:Microsoft.WindowsAzure.Storage.StorageUri" />-Objekt.</param>
        <param name="uri2">Das zweite zu vergleichende <see cref="T:Microsoft.WindowsAzure.Storage.StorageUri" />-Objekt.</param>
        <summary>
            Vergleicht zwei <see cref="T:Microsoft.WindowsAzure.Storage.StorageUri" /> Objekte für nicht vorhandene Äquivalenz.
            </summary>
        <returns>
          <c>"true"</c> Wenn die <see cref="T:Microsoft.WindowsAzure.Storage.StorageUri" /> Objekte antivalenter Werte aufweisen, andernfalls <c>"false"</c>.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="PrimaryUri">
      <MemberSignature Language="C#" Value="public Uri PrimaryUri { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Uri PrimaryUri" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Storage.StorageUri.PrimaryUri" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property PrimaryUri As Uri" />
      <MemberSignature Language="F#" Value="member this.PrimaryUri : Uri" Usage="Microsoft.WindowsAzure.Storage.StorageUri.PrimaryUri" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Uri</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Der Endpunkt für den primären Speicherort für das Speicherkonto an.
            </summary>
        <value>Die <see cref="T:System.Uri" /> für den primären Endpunkt.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SecondaryUri">
      <MemberSignature Language="C#" Value="public Uri SecondaryUri { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Uri SecondaryUri" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Storage.StorageUri.SecondaryUri" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property SecondaryUri As Uri" />
      <MemberSignature Language="F#" Value="member this.SecondaryUri : Uri" Usage="Microsoft.WindowsAzure.Storage.StorageUri.SecondaryUri" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Uri</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Der Endpunkt für den sekundären Standort für das Speicherkonto an.
            </summary>
        <value>Die <see cref="T:System.Uri" /> für den sekundären Endpunkt.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ToString">
      <MemberSignature Language="C#" Value="public override string ToString ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance string ToString() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.StorageUri.ToString" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Function ToString () As String" />
      <MemberSignature Language="F#" Value="override this.ToString : unit -&gt; string" Usage="storageUri.ToString " />
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
            Gibt einen <see cref="T:System.String" /> zurück, der diese Instanz darstellt.
            </summary>
        <returns>
            Ein <see cref="T:System.String" />, der diese Instanz darstellt.
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>