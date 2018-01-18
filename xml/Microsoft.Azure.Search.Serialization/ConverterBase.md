<Type Name="ConverterBase" FullName="Microsoft.Azure.Search.Serialization.ConverterBase">
  <TypeSignature Language="C#" Value="public abstract class ConverterBase : Newtonsoft.Json.JsonConverter" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract beforefieldinit ConverterBase extends Newtonsoft.Json.JsonConverter" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Search.Serialization.ConverterBase" />
  <TypeSignature Language="VB.NET" Value="Public MustInherit Class ConverterBase&#xA;Inherits JsonConverter" />
  <TypeSignature Language="F#" Value="type ConverterBase = class&#xA;    inherit JsonConverter" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Search</AssemblyName>
    <AssemblyVersion>3.0.0.0</AssemblyVersion>
    <AssemblyVersion>4.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>Newtonsoft.Json.JsonConverter</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="390ee-101">Die Basisklasse für benutzerdefinierte JsonConverters.</span><span class="sxs-lookup"><span data-stu-id="390ee-101">Base class for custom JsonConverters.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="protected ConverterBase ();" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Search.Serialization.ConverterBase.#ctor" />
      <MemberSignature Language="VB.NET" Value="Protected Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>To be added.</summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Advance">
      <MemberSignature Language="C#" Value="protected void Advance (Newtonsoft.Json.JsonReader reader);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig instance void Advance(class Newtonsoft.Json.JsonReader reader) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Search.Serialization.ConverterBase.Advance(Newtonsoft.Json.JsonReader)" />
      <MemberSignature Language="VB.NET" Value="Protected Sub Advance (reader As JsonReader)" />
      <MemberSignature Language="F#" Value="member this.Advance : Newtonsoft.Json.JsonReader -&gt; unit" Usage="converterBase.Advance reader" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="reader" Type="Newtonsoft.Json.JsonReader" />
      </Parameters>
      <Docs>
        <param name="reader"><span data-ttu-id="390ee-102">Zum Fortsetzen der JSON-Reader.</span><span class="sxs-lookup"><span data-stu-id="390ee-102">The JSON reader to advance.</span></span></param>
        <summary>
            <span data-ttu-id="390ee-103">Verschiebt den angegebenen JSON-Reader oder löst eine JsonSerializationException aus, wenn es kann nicht gesetzt werden.</span><span class="sxs-lookup"><span data-stu-id="390ee-103">Advances the given JSON reader, or throws a JsonSerializationException if it cannot be advanced.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Expect">
      <MemberSignature Language="C#" Value="protected void Expect (Newtonsoft.Json.JsonReader reader, Newtonsoft.Json.JsonToken expectedToken, object expectedValue = null);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig instance void Expect(class Newtonsoft.Json.JsonReader reader, valuetype Newtonsoft.Json.JsonToken expectedToken, object expectedValue) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Search.Serialization.ConverterBase.Expect(Newtonsoft.Json.JsonReader,Newtonsoft.Json.JsonToken,System.Object)" />
      <MemberSignature Language="VB.NET" Value="Protected Sub Expect (reader As JsonReader, expectedToken As JsonToken, Optional expectedValue As Object = null)" />
      <MemberSignature Language="F#" Value="member this.Expect : Newtonsoft.Json.JsonReader * Newtonsoft.Json.JsonToken * obj -&gt; unit" Usage="converterBase.Expect (reader, expectedToken, expectedValue)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="reader" Type="Newtonsoft.Json.JsonReader" />
        <Parameter Name="expectedToken" Type="Newtonsoft.Json.JsonToken" />
        <Parameter Name="expectedValue" Type="System.Object" />
      </Parameters>
      <Docs>
        <param name="reader"><span data-ttu-id="390ee-104">Der JSON-Reader.</span><span class="sxs-lookup"><span data-stu-id="390ee-104">The JSON reader.</span></span></param>
        <param name="expectedToken"><span data-ttu-id="390ee-105">Das JSON-Token, das auf dem der Reader positioniert werden soll.</span><span class="sxs-lookup"><span data-stu-id="390ee-105">The JSON token on which the reader is expected to be positioned.</span></span></param>
        <param name="expectedValue"><span data-ttu-id="390ee-106">Dies ist optional; Der erwartete Wert des aktuellen Tokens JSON.</span><span class="sxs-lookup"><span data-stu-id="390ee-106">Optional; The expected value of the current JSON token.</span></span></param>
        <summary>
            <span data-ttu-id="390ee-107">Bestätigt, dass das angegebene JSON-Reader mit dem erwarteten Typ auf ein Token positioniert ist.</span><span class="sxs-lookup"><span data-stu-id="390ee-107">Asserts that the given JSON reader is positioned on a token with the expected type.</span></span> <span data-ttu-id="390ee-108">Optional bestätigt, dass der Wert des Tokens mit einen angegebenen erwarteten Wert entspricht.</span><span class="sxs-lookup"><span data-stu-id="390ee-108">Optionally asserts that the value of the token matches a given expected value.</span></span> <span data-ttu-id="390ee-109">Wenn einer der Assertionen fehlschlägt, löst diese Methode eine JsonSerializationException an.</span><span class="sxs-lookup"><span data-stu-id="390ee-109">If any of the assertions fail, this method throws a JsonSerializationException.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Expect&lt;TValue&gt;">
      <MemberSignature Language="C#" Value="protected TValue Expect&lt;TValue&gt; (Newtonsoft.Json.JsonReader reader, Newtonsoft.Json.JsonToken expectedToken, object expectedValue = null);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig instance !!TValue Expect&lt;TValue&gt;(class Newtonsoft.Json.JsonReader reader, valuetype Newtonsoft.Json.JsonToken expectedToken, object expectedValue) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Search.Serialization.ConverterBase.Expect``1(Newtonsoft.Json.JsonReader,Newtonsoft.Json.JsonToken,System.Object)" />
      <MemberSignature Language="VB.NET" Value="Protected Function Expect(Of TValue) (reader As JsonReader, expectedToken As JsonToken, Optional expectedValue As Object = null) As TValue" />
      <MemberSignature Language="F#" Value="member this.Expect : Newtonsoft.Json.JsonReader * Newtonsoft.Json.JsonToken * obj -&gt; 'Value" Usage="converterBase.Expect (reader, expectedToken, expectedValue)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>TValue</ReturnType>
      </ReturnValue>
      <TypeParameters>
        <TypeParameter Name="TValue" />
      </TypeParameters>
      <Parameters>
        <Parameter Name="reader" Type="Newtonsoft.Json.JsonReader" />
        <Parameter Name="expectedToken" Type="Newtonsoft.Json.JsonToken" />
        <Parameter Name="expectedValue" Type="System.Object" />
      </Parameters>
      <Docs>
        <typeparam name="TValue"><span data-ttu-id="390ee-110">Der erwartete Typ des Werts des aktuellen JSON-Tokens.</span><span class="sxs-lookup"><span data-stu-id="390ee-110">The expected type of the value of the current JSON token.</span></span></typeparam>
        <param name="reader"><span data-ttu-id="390ee-111">Der JSON-Reader.</span><span class="sxs-lookup"><span data-stu-id="390ee-111">The JSON reader.</span></span></param>
        <param name="expectedToken"><span data-ttu-id="390ee-112">Das JSON-Token, das auf dem der Reader positioniert werden soll.</span><span class="sxs-lookup"><span data-stu-id="390ee-112">The JSON token on which the reader is expected to be positioned.</span></span></param>
        <param name="expectedValue"><span data-ttu-id="390ee-113">Dies ist optional; Der erwartete Wert des aktuellen Tokens JSON.</span><span class="sxs-lookup"><span data-stu-id="390ee-113">Optional; The expected value of the current JSON token.</span></span></param>
        <summary>
            <span data-ttu-id="390ee-114">Bestätigt, dass die angegebene JSON-Reader sich auf ein Token mit dem erwarteten Typ befindet und den Wert des Tokens Ruft, sofern vorhanden.</span><span class="sxs-lookup"><span data-stu-id="390ee-114">Asserts that the given JSON reader is positioned on a token with the expected type and retrieves the value of the token, if any.</span></span> <span data-ttu-id="390ee-115">Optional bestätigt, dass der Wert des Tokens mit einen angegebenen erwarteten Wert entspricht.</span><span class="sxs-lookup"><span data-stu-id="390ee-115">Optionally asserts that the value of the token matches a given expected value.</span></span> <span data-ttu-id="390ee-116">Wenn einer der Assertionen fehlschlägt, löst diese Methode eine JsonSerializationException an.</span><span class="sxs-lookup"><span data-stu-id="390ee-116">If any of the assertions fail, this method throws a JsonSerializationException.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="390ee-117">Der Wert des aktuellen JSON-webtoken oder default(TValue), wenn das aktuelle Token keinen Wert verfügt.</span><span class="sxs-lookup"><span data-stu-id="390ee-117">The value of the current JSON token, or default(TValue) if the current token has no value.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ExpectAndAdvance">
      <MemberSignature Language="C#" Value="protected void ExpectAndAdvance (Newtonsoft.Json.JsonReader reader, Newtonsoft.Json.JsonToken expectedToken, object expectedValue = null);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig instance void ExpectAndAdvance(class Newtonsoft.Json.JsonReader reader, valuetype Newtonsoft.Json.JsonToken expectedToken, object expectedValue) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Search.Serialization.ConverterBase.ExpectAndAdvance(Newtonsoft.Json.JsonReader,Newtonsoft.Json.JsonToken,System.Object)" />
      <MemberSignature Language="VB.NET" Value="Protected Sub ExpectAndAdvance (reader As JsonReader, expectedToken As JsonToken, Optional expectedValue As Object = null)" />
      <MemberSignature Language="F#" Value="member this.ExpectAndAdvance : Newtonsoft.Json.JsonReader * Newtonsoft.Json.JsonToken * obj -&gt; unit" Usage="converterBase.ExpectAndAdvance (reader, expectedToken, expectedValue)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="reader" Type="Newtonsoft.Json.JsonReader" />
        <Parameter Name="expectedToken" Type="Newtonsoft.Json.JsonToken" />
        <Parameter Name="expectedValue" Type="System.Object" />
      </Parameters>
      <Docs>
        <param name="reader"><span data-ttu-id="390ee-118">Der JSON-Reader.</span><span class="sxs-lookup"><span data-stu-id="390ee-118">The JSON reader.</span></span></param>
        <param name="expectedToken"><span data-ttu-id="390ee-119">Das JSON-Token, das auf dem der Reader positioniert werden soll.</span><span class="sxs-lookup"><span data-stu-id="390ee-119">The JSON token on which the reader is expected to be positioned.</span></span></param>
        <param name="expectedValue"><span data-ttu-id="390ee-120">Dies ist optional; Der erwartete Wert des aktuellen Tokens JSON.</span><span class="sxs-lookup"><span data-stu-id="390ee-120">Optional; The expected value of the current JSON token.</span></span></param>
        <summary>
            <span data-ttu-id="390ee-121">Bestätigt, dass das angegebene JSON-Reader mit dem erwarteten Typ auf ein Token positioniert ist.</span><span class="sxs-lookup"><span data-stu-id="390ee-121">Asserts that the given JSON reader is positioned on a token with the expected type.</span></span> <span data-ttu-id="390ee-122">Optional bestätigt, dass der Wert des Tokens mit einen angegebenen erwarteten Wert entspricht.</span><span class="sxs-lookup"><span data-stu-id="390ee-122">Optionally asserts that the value of the token matches a given expected value.</span></span> <span data-ttu-id="390ee-123">Wenn einer der Assertionen fehlschlägt, löst diese Methode eine JsonSerializationException an.</span><span class="sxs-lookup"><span data-stu-id="390ee-123">If any of the assertions fail, this method throws a JsonSerializationException.</span></span> <span data-ttu-id="390ee-124">Andernfalls versucht diese Methode, die JSON-Reader zum nächsten Position zu gelangen.</span><span class="sxs-lookup"><span data-stu-id="390ee-124">Otherwise, this method attempts to advance the JSON reader to the next position.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ExpectAndAdvance&lt;TValue&gt;">
      <MemberSignature Language="C#" Value="protected TValue ExpectAndAdvance&lt;TValue&gt; (Newtonsoft.Json.JsonReader reader, Newtonsoft.Json.JsonToken expectedToken, object expectedValue = null);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig instance !!TValue ExpectAndAdvance&lt;TValue&gt;(class Newtonsoft.Json.JsonReader reader, valuetype Newtonsoft.Json.JsonToken expectedToken, object expectedValue) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Search.Serialization.ConverterBase.ExpectAndAdvance``1(Newtonsoft.Json.JsonReader,Newtonsoft.Json.JsonToken,System.Object)" />
      <MemberSignature Language="VB.NET" Value="Protected Function ExpectAndAdvance(Of TValue) (reader As JsonReader, expectedToken As JsonToken, Optional expectedValue As Object = null) As TValue" />
      <MemberSignature Language="F#" Value="member this.ExpectAndAdvance : Newtonsoft.Json.JsonReader * Newtonsoft.Json.JsonToken * obj -&gt; 'Value" Usage="converterBase.ExpectAndAdvance (reader, expectedToken, expectedValue)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>TValue</ReturnType>
      </ReturnValue>
      <TypeParameters>
        <TypeParameter Name="TValue" />
      </TypeParameters>
      <Parameters>
        <Parameter Name="reader" Type="Newtonsoft.Json.JsonReader" />
        <Parameter Name="expectedToken" Type="Newtonsoft.Json.JsonToken" />
        <Parameter Name="expectedValue" Type="System.Object" />
      </Parameters>
      <Docs>
        <typeparam name="TValue"><span data-ttu-id="390ee-125">Der erwartete Typ des Werts des aktuellen JSON-Tokens.</span><span class="sxs-lookup"><span data-stu-id="390ee-125">The expected type of the value of the current JSON token.</span></span></typeparam>
        <param name="reader"><span data-ttu-id="390ee-126">Der JSON-Reader.</span><span class="sxs-lookup"><span data-stu-id="390ee-126">The JSON reader.</span></span></param>
        <param name="expectedToken"><span data-ttu-id="390ee-127">Das JSON-Token, das auf dem der Reader positioniert werden soll.</span><span class="sxs-lookup"><span data-stu-id="390ee-127">The JSON token on which the reader is expected to be positioned.</span></span></param>
        <param name="expectedValue"><span data-ttu-id="390ee-128">Dies ist optional; Der erwartete Wert des aktuellen Tokens JSON.</span><span class="sxs-lookup"><span data-stu-id="390ee-128">Optional; The expected value of the current JSON token.</span></span></param>
        <summary>
            <span data-ttu-id="390ee-129">Bestätigt, dass die angegebene JSON-Reader sich auf ein Token mit dem erwarteten Typ befindet und den Wert des Tokens Ruft, sofern vorhanden.</span><span class="sxs-lookup"><span data-stu-id="390ee-129">Asserts that the given JSON reader is positioned on a token with the expected type and retrieves the value of the token, if any.</span></span> <span data-ttu-id="390ee-130">Optional bestätigt, dass der Wert des Tokens mit einen angegebenen erwarteten Wert entspricht.</span><span class="sxs-lookup"><span data-stu-id="390ee-130">Optionally asserts that the value of the token matches a given expected value.</span></span> <span data-ttu-id="390ee-131">Wenn einer der Assertionen fehlschlägt, löst diese Methode eine JsonSerializationException an.</span><span class="sxs-lookup"><span data-stu-id="390ee-131">If any of the assertions fail, this method throws a JsonSerializationException.</span></span> <span data-ttu-id="390ee-132">Andernfalls versucht diese Methode, die JSON-Reader zum nächsten Position zu gelangen.</span><span class="sxs-lookup"><span data-stu-id="390ee-132">Otherwise, this method attempts to advance the JSON reader to the next position.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="390ee-133">Der Wert der JSON-webtoken vor dem Vorlauf der Leser oder default(TValue), wenn das Token über keinen Wert verfügt.</span><span class="sxs-lookup"><span data-stu-id="390ee-133">The value of the JSON token before advancing the reader, or default(TValue) if the token has no value.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>