<Type Name="LocalStoreSettings" FullName="System.Fabric.LocalStoreSettings">
  <TypeSignature Language="C#" Value="public abstract class LocalStoreSettings" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract beforefieldinit LocalStoreSettings extends System.Object" />
  <TypeSignature Language="DocId" Value="T:System.Fabric.LocalStoreSettings" />
  <TypeSignature Language="VB.NET" Value="Public MustInherit Class LocalStoreSettings" />
  <TypeSignature Language="F#" Value="type LocalStoreSettings = class" />
  <AssemblyInfo>
    <AssemblyName>System.Fabric</AssemblyName>
    <AssemblyVersion>6.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
      <para><span data-ttu-id="e8a28-101">Stellt die optionseinstellungen für einen lokalen Speicher dar.</span><span class="sxs-lookup"><span data-stu-id="e8a28-101">Represents the option settings for a local store.</span></span></para>
    </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="protected LocalStoreSettings (System.Fabric.LocalStoreKind storeKind);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig specialname rtspecialname instance void .ctor(valuetype System.Fabric.LocalStoreKind storeKind) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.LocalStoreSettings.#ctor(System.Fabric.LocalStoreKind)" />
      <MemberSignature Language="VB.NET" Value="Protected Sub New (storeKind As LocalStoreKind)" />
      <MemberSignature Language="F#" Value="new System.Fabric.LocalStoreSettings : System.Fabric.LocalStoreKind -&gt; System.Fabric.LocalStoreSettings" Usage="new System.Fabric.LocalStoreSettings storeKind" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="storeKind" Type="System.Fabric.LocalStoreKind" />
      </Parameters>
      <Docs>
        <param name="storeKind">
          <para><span data-ttu-id="e8a28-102">Ein <see cref="T:System.Fabric.LocalStoreKind" /> Objekt, das den Typ des Speicheranbieters darstellt.</span><span class="sxs-lookup"><span data-stu-id="e8a28-102">A <see cref="T:System.Fabric.LocalStoreKind" /> object representing the store provider type.</span></span></para>
        </param>
        <summary>
          <para><span data-ttu-id="e8a28-103">Initialisiert eine neue Instanz der Klasse mit dem angegebenen Anbieter Speichertyp.</span><span class="sxs-lookup"><span data-stu-id="e8a28-103">Initializes a new instance of the class with the specified store provider type.</span></span></para>
        </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="StoreKind">
      <MemberSignature Language="C#" Value="public System.Fabric.LocalStoreKind StoreKind { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Fabric.LocalStoreKind StoreKind" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.LocalStoreSettings.StoreKind" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property StoreKind As LocalStoreKind" />
      <MemberSignature Language="F#" Value="member this.StoreKind : System.Fabric.LocalStoreKind" Usage="System.Fabric.LocalStoreSettings.StoreKind" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.LocalStoreKind</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para><span data-ttu-id="e8a28-104">Ruft den Typ des Speicheranbieters an.</span><span class="sxs-lookup"><span data-stu-id="e8a28-104">Gets the store provider type.</span></span></para>
        </summary>
        <value>
          <para><span data-ttu-id="e8a28-105">Typ des Speicheranbieters als ein <see cref="T:System.Fabric.LocalStoreKind" /> Objekt.</span><span class="sxs-lookup"><span data-stu-id="e8a28-105">The store provider type as a <see cref="T:System.Fabric.LocalStoreKind" /> object.</span></span></para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>