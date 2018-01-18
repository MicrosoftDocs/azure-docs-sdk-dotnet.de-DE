<Type Name="MobileServiceIsoDateTimeConverter" FullName="Microsoft.WindowsAzure.MobileServices.MobileServiceIsoDateTimeConverter">
  <TypeSignature Language="C#" Value="public class MobileServiceIsoDateTimeConverter : Newtonsoft.Json.Converters.IsoDateTimeConverter" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit MobileServiceIsoDateTimeConverter extends Newtonsoft.Json.Converters.IsoDateTimeConverter" />
  <TypeSignature Language="DocId" Value="T:Microsoft.WindowsAzure.MobileServices.MobileServiceIsoDateTimeConverter" />
  <TypeSignature Language="VB.NET" Value="Public Class MobileServiceIsoDateTimeConverter&#xA;Inherits IsoDateTimeConverter" />
  <TypeSignature Language="F#" Value="type MobileServiceIsoDateTimeConverter = class&#xA;    inherit IsoDateTimeConverter" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Mobile.Client</AssemblyName>
    <AssemblyVersion>4.0.0.0</AssemblyVersion>
    <AssemblyVersion>4.0.2.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>Newtonsoft.Json.Converters.IsoDateTimeConverter</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="3e442-101">Konvertiert "DateTime" und "DateTimeOffset"-Objekts in UTC DateTime und erstellt eine ISO-Zeichenfolgendarstellung, indem ToUniversalTime bei der Serialisierung und ToLocalTime bei der Deserialisierung.</span><span class="sxs-lookup"><span data-stu-id="3e442-101">Converts DateTime and DateTimeOffset object into UTC DateTime and creates a ISO string representation by calling ToUniversalTime on serialization and ToLocalTime on deserialization.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public MobileServiceIsoDateTimeConverter ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.MobileServices.MobileServiceIsoDateTimeConverter.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Mobile.Client</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.2.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="3e442-102">Erstellt eine neue Instanz von <see cref="T:Microsoft.WindowsAzure.MobileServices.MobileServiceIsoDateTimeConverter" />.</span><span class="sxs-lookup"><span data-stu-id="3e442-102">Creates a new instance of <see cref="T:Microsoft.WindowsAzure.MobileServices.MobileServiceIsoDateTimeConverter" />.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ReadJson">
      <MemberSignature Language="C#" Value="public override object ReadJson (Newtonsoft.Json.JsonReader reader, Type objectType, object existingValue, Newtonsoft.Json.JsonSerializer serializer);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance object ReadJson(class Newtonsoft.Json.JsonReader reader, class System.Type objectType, object existingValue, class Newtonsoft.Json.JsonSerializer serializer) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.MobileServices.MobileServiceIsoDateTimeConverter.ReadJson(Newtonsoft.Json.JsonReader,System.Type,System.Object,Newtonsoft.Json.JsonSerializer)" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Function ReadJson (reader As JsonReader, objectType As Type, existingValue As Object, serializer As JsonSerializer) As Object" />
      <MemberSignature Language="F#" Value="override this.ReadJson : Newtonsoft.Json.JsonReader * Type * obj * Newtonsoft.Json.JsonSerializer -&gt; obj" Usage="mobileServiceIsoDateTimeConverter.ReadJson (reader, objectType, existingValue, serializer)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Mobile.Client</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.2.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Object</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="reader" Type="Newtonsoft.Json.JsonReader" />
        <Parameter Name="objectType" Type="System.Type" />
        <Parameter Name="existingValue" Type="System.Object" />
        <Parameter Name="serializer" Type="Newtonsoft.Json.JsonSerializer" />
      </Parameters>
      <Docs>
        <param name="reader"><span data-ttu-id="3e442-103">Der <see cref="T:Newtonsoft.Json.JsonReader" />, aus dem gelesen werden soll.</span><span class="sxs-lookup"><span data-stu-id="3e442-103">The <see cref="T:Newtonsoft.Json.JsonReader" /> to read from.</span></span></param>
        <param name="objectType"><span data-ttu-id="3e442-104">Typ des Objekts.</span><span class="sxs-lookup"><span data-stu-id="3e442-104">Type of the object.</span></span></param>
        <param name="existingValue"><span data-ttu-id="3e442-105">Der vorhandene Wert des Objekts, das gelesen wird.</span><span class="sxs-lookup"><span data-stu-id="3e442-105">The existing value of object being read.</span></span></param>
        <param name="serializer"><span data-ttu-id="3e442-106">Das aufrufende Serialisierungsprogramm.</span><span class="sxs-lookup"><span data-stu-id="3e442-106">The calling serializer.</span></span></param>
        <summary>
            <span data-ttu-id="3e442-107">Liest die JSON-Darstellung des Objekts an.</span><span class="sxs-lookup"><span data-stu-id="3e442-107">Reads the JSON representation of the object.</span></span>
            </summary>
        <returns><span data-ttu-id="3e442-108">Der Objektwert.</span><span class="sxs-lookup"><span data-stu-id="3e442-108">The object value.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="WriteJson">
      <MemberSignature Language="C#" Value="public override void WriteJson (Newtonsoft.Json.JsonWriter writer, object value, Newtonsoft.Json.JsonSerializer serializer);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance void WriteJson(class Newtonsoft.Json.JsonWriter writer, object value, class Newtonsoft.Json.JsonSerializer serializer) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.MobileServices.MobileServiceIsoDateTimeConverter.WriteJson(Newtonsoft.Json.JsonWriter,System.Object,Newtonsoft.Json.JsonSerializer)" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Sub WriteJson (writer As JsonWriter, value As Object, serializer As JsonSerializer)" />
      <MemberSignature Language="F#" Value="override this.WriteJson : Newtonsoft.Json.JsonWriter * obj * Newtonsoft.Json.JsonSerializer -&gt; unit" Usage="mobileServiceIsoDateTimeConverter.WriteJson (writer, value, serializer)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Mobile.Client</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.2.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="writer" Type="Newtonsoft.Json.JsonWriter" />
        <Parameter Name="value" Type="System.Object" />
        <Parameter Name="serializer" Type="Newtonsoft.Json.JsonSerializer" />
      </Parameters>
      <Docs>
        <param name="writer"><span data-ttu-id="3e442-109">Der <see cref="T:Newtonsoft.Json.JsonWriter" />, in den geschrieben werden soll.</span><span class="sxs-lookup"><span data-stu-id="3e442-109">The <see cref="T:Newtonsoft.Json.JsonWriter" /> to write to.</span></span></param>
        <param name="value"><span data-ttu-id="3e442-110">Der Wert.</span><span class="sxs-lookup"><span data-stu-id="3e442-110">The value.</span></span></param>
        <param name="serializer"><span data-ttu-id="3e442-111">Das aufrufende Serialisierungsprogramm.</span><span class="sxs-lookup"><span data-stu-id="3e442-111">The calling serializer.</span></span></param>
        <summary>
            <span data-ttu-id="3e442-112">Schreibt die JSON-Darstellung des Objekts an.</span><span class="sxs-lookup"><span data-stu-id="3e442-112">Writes the JSON representation of the object.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>